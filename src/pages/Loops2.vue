<script>
export default {
    data() {
      return{
          nama : "Ayu agustin",
          tahunlahir : 1998,
          kotalahir : "Tangerang"
      }  
    },
    methods:{
        next(){
            this.tahunlahir += 1;
        }
    },
    mounted(){
        this.tahunlahir = 2021 - this.tahunlahir;
    }
}
</script>