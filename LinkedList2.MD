Struct node
{
  int data;
  Node* Link;
}

Node* A;
A = NULL;  // empty list

Node* temp = (Node*)malloc(sizeof(Node))
(*temp).data = 5;
(*temp).link = NULL;
--------------------------------------------------

Node* A;
A = NULL;

Node* temp = new Node();
temp.data = 2;
temp.link = NULL;
A = temp;

temp = new Node();
temp.data = 4;
temp.link = NULL;
