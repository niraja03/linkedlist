# linkedlist

Flow must be remembered :
always :
class Node{
public:
    int data;
    Node* next;
    Node(int val) {
        data = val;
        next =nullptr;
    }
};

start ur main fn

create ur nodes (ex: Node* first = new Node(4);

link the nodes together (ex: first->next = second;

display the LL :
    Node* temp= first; //strating from
    while (temp != nullptr)
    {
        cout << temp->data<<" ";
        temp = temp->next;
    }
    return 0;
    }

