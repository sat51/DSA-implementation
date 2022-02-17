public class Queue_using_ll {
    class Node
    {
        int data;
        Node next;
        public Node(int data)
        {
            this.data = data;
        }
    }
    Node front,rear;
    void Enqueue(int data)
    {
        Node n = new Node(data);
        if(front == null)
        {
            front = rear = n;
        }
        else
        {
            rear.next = n;
            rear = n;
        }
    }
    int deque() throws Exception
    {
        if(front == null)
            throw new Exception("queue is empty");
        int val= front.data;
        front = front.next;
        return val;

    }
}
