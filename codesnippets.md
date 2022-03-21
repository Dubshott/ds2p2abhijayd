{% include navigation.html %}

This is where all the code snippets go!

# Week 1

**Linked list and Java Generic T**

```
public static void main(String[] args) {

    //linked list creation for challenge sentence
    LinkedList<String> = sentence = new LinkedList<String>();

```

```
//generic T allows any data type to be used when class is called
public class queue<T> {

    private ArrayList<T> list = new ArrayList<T>();

    public queue() {}

    public void push(T data){
        list.add(data);
    }
```

**Queue Add and Delete**

```
//add data to queue
    public void push(T data){
        list.add(data);
    }

    //remove from queue (pop)
    public void pop(){
        //if list is not empty
        if(!list.isEmpty()){
            //remove item from list
            list.remove(0);
        }
        else{

            System.out.println("null");
            return null;
        }
    }
    
```

**Merge 2 Queues**
```
while((q1.display() != null) || (q2.display() != null)) {
            try {
                //checks whether q1's output or q2's output is smaller
                if((q1.peek() < q2.peek()))  {
                    output.push(q1.peek());
                    q1.pop();
                }
                else if((q2.peek() < q1.peek()) || ((q1.peek()) == null) || (q2.peek() == null)) {
                    output.push(q2.peek());
                    q2.pop();
                }
                //when a list is null, move to this section
                //appends any remaining values
            } catch (Exception e) {
                if(q1.peek() == null) {
                    output.push(q2.peek());
                    q2.pop();
                    break;
                }
                else if(q2.peek() == null) {
                    output.push(q1.peek());
                    q1.pop();
                    break;
                }
            }
        }

```

**Build Stack and reverse Queue Order**

```
        //move queue elements into stack
        int j = start.length();
        for(int i = 0; i < j; i++) {
            output.push(start.peek());
            start.pop();
        }

        //put stack into a list
        //putting a queue into a stack reverses order
        //first in first out to first in last out
        ArrayList<Integer> output_list = new ArrayList<Integer>();
```




# Week 0

**Code Snippets**
1. [Create Hashmap Menu](https://github.com/Dubshott/ds2p2abhijayd/blob/main/menu.java)
2. [Swap Numbers](https://github.com/Dubshott/ds2p2abhijayd/blob/main/swapper.java)
3. [Matrix](https://github.com/Dubshott/ds2p2abhijayd/blob/main/matrix.java)
