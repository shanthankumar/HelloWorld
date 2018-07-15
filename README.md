# LinkedList
class LinkedList{
Node Head;
static class Node{
int data;
Node next;
public Node(int x){
data=d;
next=null;
}
}
public void printAll(){
Node n=Head;
While(n!=null){
system.out.print(n.data+" ");
n=n.next;
}
public static void main(String[] args){
Linkedlist l=new LinkedList();
l.Head=new Node(10);
Node second=new Node(20);
Node third=new Node(30);
l.Head.next=second;
second.next=third;
l.printAll();
}
}
