# day07
Class
3. Write a “person” class to hold all the details.

class person{
  constructor(name,gender,age){
    this.name=name;
    this.gender=gender;
    this.age=age;
  }
  nameprint(){ 
    return this.name;
  }
  ageprint(){
    return this.age;}
}
var c1=new person("John","male",23);
console.log("My name is "+c1.nameprint()+" and my age is "+c1.ageprint());
class vijay extends person{
  constructor(name,gender,age){
    super(name,gender,age);
  }
  show(){
    return this.nameprint(),this.age;
}}
var c2=new vijay("Vijay","male",28);
console.log("My name is "+c2.nameprint()+" and my age is "+c2.ageprint());



