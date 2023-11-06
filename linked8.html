


<html>
<head>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
<h3>Code:</h3>
    <div id="div4">
        <pre>
#include &lt;stdio.h&gt; 
#include &lt;stdlib.h&gt; 
#include &lt;string.h&gt; 


struct node {
    struct node *previous;
    char str[10];
    struct node *next;
};

struct node *start = NULL, *last = NULL, *traverse, *newnode, *temp;

int insertatbeg(int count) {
    if (start == NULL) {
        newnode = (struct node *)malloc(sizeof(struct node));
        printf("Enter the string: ");
        scanf("%s", newnode->str);
        newnode->next = NULL;
        start = last = newnode;
        count++;
    } else {
        newnode = (struct node *)malloc(sizeof(struct node));
        printf("Enter the string: ");
        scanf("%s", newnode->str);
        newnode->next = start;
        newnode->previous = NULL;
        start->previous = newnode;
        start = newnode;
        last->next = start;
        count++;
    }
    return count;
}

int insertatend(int count) {
    if (start == NULL) {
        newnode = (struct node *)malloc(sizeof(struct node));
        printf("Enter the string: ");
        scanf("%s", newnode->str);
        newnode->next = NULL;
        start = newnode;
        newnode->previous = start;
        last = start;
        count++;
    } else {
        traverse = start;
        newnode = (struct node *)malloc(sizeof(struct node));
        printf("Enter the string: ");
        scanf("%s", newnode->str);
        while (traverse->next != start) {
            traverse = traverse->next;
        }
        traverse->next = newnode;
        newnode->previous = traverse;
        newnode->next = start;
        last = newnode;
        count++;
    }
    return count;
}

int insertatpos(int count) {
    int pos, i;
    printf("Enter the position: ");
    scanf("%d", &pos);

    if (pos <= 0) {
        printf("Invalid position\n");
    } else if (pos == count + 1) {
        count = insertatend(count);
    } else if (pos > count + 1) {
        printf("Invalid position\n");
    } else if (pos == 1) {
        count = insertatbeg(count);
    } else if (pos >= 2 && pos <= count) {
        newnode = (struct node *)malloc(sizeof(struct node));
        printf("Enter the string: ");
        scanf("%s", newnode->str);
        traverse = start;
        for (i = 1; i < pos - 1; i++) {
            traverse = traverse->next;
        }
        newnode->next = traverse->next;
        newnode->previous = traverse;
        traverse->next->previous = newnode;
        traverse->next = newnode;
        count++;
    }
    return count;
}

int deleteatbeg(int count) {
    if (start == NULL) {
        printf("List is empty\n");
    } else if (start->next == start) {
        printf("Deleted string is %s\n", start->str);
        free(start);
        start = NULL;
        count--;
    } else {
        temp = start;
        printf("Deleted string is %s\n", temp->str);
        start = start->next;
        start->previous = NULL;
        last->next = start;
        free(temp);
        count--;
    }
    return count;
}

int deleteatend(int count) {
    if (start == NULL) {
        printf("List is empty\n");
    } else if (start->next == start) {
        printf("Deleted string is %s\n", start->str);
        free(start);
        start = NULL;
        count--;
    } else {
        temp = start;
        while (temp->next != start) {
            traverse = temp;
            temp = temp->next;
        }
        traverse->next = start;
        printf("Deleted string is %s\n", temp->str);
        free(temp);
        count--;
    }
    return count;
}

int deleteatpos(int count) {
    int pos, i;
    printf("Enter the position: ");
    scanf("%d", &pos);

    if (start == NULL) {
        printf("List is empty\n");
    } else if (pos <= 0) {
        printf("Invalid position\n");
    } else if (pos > count + 1) {
        printf("Invalid position\n");
    } else if (pos == 1) {
        count = deleteatbeg(count);
    } else if (pos == count) {
        count = deleteatend(count);
    } else if (pos >= 2 && pos <= count) {
        traverse = start;
        for (i = 1; i < pos - 1; i++) {
            traverse = traverse->next;
        }
        temp = traverse->next;
        printf("Deleted string is %s\n", temp->str);
        traverse->next = temp->next;
        temp->next->previous = traverse;
        free(temp);
        count--;
    }
    return count;
}

void traversing() {
    if (start == NULL) {
        printf("List is empty\n");
    } else {
        traverse = start;
        printf("String in linked list is %s\n", traverse->str);
        traverse = traverse->next;
        while (traverse != start) {
            printf("String in linked list is %s\n", traverse->str);
            traverse = traverse->next;
        }
    }
}

void searching() {
    if (start == NULL) {
        printf("List is empty\n");
    } else {
        char search[10];
        int pos = 1, f = 0;
        printf("Enter the string you want to search: ");
        scanf("%s", search);
        traverse = start;
        while (traverse->next != start) {
            if (strcmp(traverse->str, search) == 0) {
                f = 1;
                break;
            }
            traverse = traverse->next;
            pos++;
        }
        if (strcmp(traverse->str, search) == 0) {
            f = 1;
        }
        if (f == 1) {
            printf("%s is searched at location %d\n", search, pos);
        } else {
            printf("Item is not in the list\n");
        }
    }
}

void isfull() {
    newnode = (struct node *)malloc(sizeof(struct node));
    if (newnode == NULL) {
        printf("List is full\n");
    } else {
        printf("List is not full\n");
    }
}

void isempty() {
    if (start == NULL) {
        printf("List is empty\n");
    } else {
        printf("List is not empty\n");
    }
}


int main() {
    int ch, count = 0;

    while (1) {
        printf("\n1. Insert at beginning\n");
        printf("2. Insert at end\n");
        printf("3. Insert at position\n");
        printf("4. Delete at beginning\n");
        printf("5. Delete at end\n");
        printf("6. Delete at position\n");
        printf("7. Traversing\n");
        printf("8. Isfull\n");
        printf("9. Isempty\n");
     
        printf("10. Searching\n");
        
        printf("13. Exit\n");
        printf("Enter your choice: ");
        scanf("%d", &ch);

        switch (ch) {
            case 1:
                count = insertatbeg(count);
                break;
            case 2:
                count = insertatend(count);
                break;
            case 3:
                count = insertatpos(count);
                break;
            case 4:
                count = deleteatbeg(count);
                break;
            case 5:
                count = deleteatend(count);
                break;
            case 6:
                count = deleteatpos(count);
                break;
            case 7:
                traversing();
                break;
            case 8:
                isfull();
                break;
            case 9:
                isempty();
                break;
            
            case 10:
                searching();
                break;
            
            case 11:
                exit(1);
            default:
                printf("Enter the valid number\n");
        }
    }

    return 0;
}





        </pre>
    </div>
<h3>output</h3>
    <div id="div5">
        <pre>


1. Insert at beginning
2. Insert at end
3. Insert at position
4. Delete at beginning
5. Delete at end
6. Delete at position
7. Traversing
8. Isfull
9. Isempty
10. Searching
11. Exit
Enter your choice: 1
Enter the string: bye

1. Insert at beginning
2. Insert at end
3. Insert at position
4. Delete at beginning
5. Delete at end
6. Delete at position
7. Traversing
8. Isfull
9. Isempty
10. Searching
11. Exit
Enter your choice: 2
Enter the string: hello

1. Insert at beginning
2. Insert at end
3. Insert at position
4. Delete at beginning
5. Delete at end
6. Delete at position
7. Traversing
8. Isfull
9. Isempty
10. Searching
11. Exit
Enter your choice: 3
Enter the position: 1
Enter the string: jai ho

1. Insert at beginning
2. Insert at end
3. Insert at position
4. Delete at beginning
5. Delete at end
6. Delete at position
7. Traversing
8. Isfull
9. Isempty
10. Searching
11. Exit
Enter your choice: 8
List is not full

1. Insert at beginning
2. Insert at end
3. Insert at position
4. Delete at beginning
5. Delete at end
6. Delete at position
7. Traversing
8. Isfull
9. Isempty
10. Searching
11. Exit
Enter your choice: 9
List is not empty


1. Insert at beginning
2. Insert at end
3. Insert at position
4. Delete at beginning
5. Delete at end
6. Delete at position
7. Traversing
8. Isfull
9. Isempty
10. Searching
11. Exit
Enter your choice: 6
Enter the position: 11
Invalid position

1. Insert at beginning
2. Insert at end
3. Insert at position
4. Delete at beginning
5. Delete at end
6. Delete at position
7. Traversing
8. Isfull
9. Isempty
10. Searching
11. Exit
Enter your choice: 11

--------------------------------
</pre>
    </div>
</body>
</html>
