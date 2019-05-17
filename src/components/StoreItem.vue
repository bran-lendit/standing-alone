<template>
    <div>
        <img :src="item.img" alt="" width="269.01px" height="269.01px" @click="open">
        <p>{{item.title}}</p>
        
    </div>
</template>
<script>
export default {
    props:{
        item: {
            img: '',
            title: '',
        }
    },
    methods: {
      open() {
          console.log('ss')
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
    div{
        display: flex;
        flex-direction: row;
        flex-wrap: wrap;
        
        padding: 0 0 50px;
        width:300px;
        height:300px;
        
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
    
    }
    }

</style>

