<template>
    <div>
        <div class="item-container">
        <img :src="item.img" alt="" width="269.01px" height="269.01px" @click="centerDialogVisible = true">
        <p>{{item.title}}</p>
        
        </div>

        <el-dialog 
        title="구매확인"
        :visible.sync="centerDialogVisible"
        width="30%"
        center>
        <div class="img-warpper"> 
             <img class = "img" :src="item.img" alt="" width="269px" height="269px">

        </div>
        <p class = "item_title">{{item.title}}</P>
        <p>{{item.text}}</p>
        <span slot="footer" class="dialog-footer">
            <el-button type="info round" @click="centerDialogVisible = false" round>장바구니</el-button>
            <el-button type="primary" @click="centerDialogVisible = false" round>구매</el-button>
            <el-button type="danger" @click="centerDialogVisible = false" round>구매취소</el-button>
            
        </span>
        </el-dialog>    
        
        
    </div>
    
</template>
<script>
export default {
      data() {
      return {
        centerDialogVisible: false
      };
    },
    props:{
        item: {
            img: '',
            title: '',
            text:'',
        }
    },
    methods: {
      open() {
        this.$alert('This is a message', 'Title', {
          confirmButtonText: 'OK',
          callback: action => {
            this.$message({
              type: 'info',
              message: `action: ${ action }`
            });
          }
        });
      }
    }
}

</script>
<style lang="scss" scoped>
    div > .item-container{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        width: 300px;
        height: 300px;
        padding: 0 0 50px;
      
        
        
    img{
      display: flex;
      justify-content: space-around;
      border-radius: 15px;
      box-shadow: 5px 5px 15px grey;
    }
    img:hover{
        opacity: 0.7;
    }
    p{
        font-weight: bold;
        font-size : 12px;
        text-align:center;
    
    }
    
    
    }
    .item_title{
        font-size:20px;
        font-weight:bold;
    }
    .el-dialog__title{
        background: black;
        opacity: 0.7;
        color:white;
    }
    .img-warpper {
        width: 100%;
        display: flex;
        justify-content: center;
    }

</style>