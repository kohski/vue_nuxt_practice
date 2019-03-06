<script>
export default {
  name: 'HelloWorld',
  data: function() {
    return {
      title:'JSX',
      message:'これは、dataに用意したメッセージです。',
    };
  },
  render: function(h){
    return (
      <div>
        <h1>{this.title}</h1>
        <p>{this.message}</p>
      </div>
    );
  }
}
</script>


<style>
/* div {……略……}
h1 {……略……}
p {……略……} */
pre {
  font-size:14pt;
  line-height: 1.25;
}
div.out {
  padding: 5px 0px;
  background-color: #eee;
  width:300px;
  height:200px;
}
div.mid {
  padding: 5px 0px;
  background-color: #ddd;
  width:200px;
  height:175px;
}
div.in {
  padding: 5px 0px;
  background-color: #ccc;
  width:100px;
  height:150px;
}
.inner {
  color:red;
  font-size:14pt;
}
.etc {
  color:green;
  background-color: #eee;
  font-size:12pt;
  padding:5px;
}
</style>