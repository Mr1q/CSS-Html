
// alert("hello world".length);
console.log("45fds fd".replace("45","asd"));

var sad="123";

var obj=new Object();
var obj2={};     //空对象
obj={
    name: "qwe",
    age: "21",
    // 不一定是字符串，数值，BOOL值都行
    email: "qq.com",
    contact :{
        phone:"asd",
        address:"bei jing"
    }
}

obj.age="21";
obj.contact.Wechar="123"; 
// 直接加任意字段
console.log(obj["contact"]["phone"]);
console.log(obj.contact);


var a =new Array();   //数组
var b=[];  //空的数组
a[0]="ads";     //假如a[5]="asd"  中间的量就是未定义的，可以取到下标为5的值，其他的值就是取不到
obj.contact.ss=a;

console.log(obj.contact);


b=["a3sd","3asd","as3d"];

for(var i=0;i<b.length;i++)
{
    console.log(b[i]);
}
for(var s in b)   //可以用in 来遍历数组  这里和FOR的区别就是for会输出未定义的量，in不会输出
{
    console.log(b[s]);
}
b.push("123");  //添加数据
b.pop(); //删掉最后一个
b.reverse(); //颠倒
b.shift(); //删除第一个元素
b.unshift(); //在第一个位置添加数据



// 函数 
let a2 =1;
function  add(x,m){
    var s=x+m;
   return  s;
}
console.log(add2(1,2,3,4,5,6,7,8,9,10));

function add2()
{
    let sum=0;
    for(let i=0;i<arguments.length;i++)
    {
        sum+=arguments[i];
    }
    return sum; //传入函数的参数集合 放在arguments这个数组里面


     // 闭包  返回函数

}


function ad(a)
{
    return function(b)
    {
        return a+b;
    }
}
var as=ad(11);
var sum=as(2);
console.log(sum);