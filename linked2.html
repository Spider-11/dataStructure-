


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


struct node {
    int data;
    struct node *next;
};

struct node *start = NULL, *last = NULL, *newnode, *traverse, *temp, *nextnode;

int insertbeg(int count) {
    newnode = (struct node*)malloc(sizeof(struct node));
    printf("Enter the data: ");
    scanf("%d", &(newnode->data));

    if (start == NULL) {
        start = last = newnode;
        newnode->next = start;
    } else {
        newnode->next = start;
        start = newnode;
        last->next = start;
    }
    count++;
    return count;
}

int insertend(int count) {
    newnode = (struct node*)malloc(sizeof(struct node));
    printf("Enter the data: ");
    scanf("%d", &(newnode->data));

    if (start == NULL) {
        start = newnode;
        newnode->next = start;
    } else {
        last = start;
        while (last->next != start) {
            last = last->next;
        }
        last->next = newnode;
        newnode->next = start;
    }
    count++;
    return count;
}

int insertpos(int count) {
    int pos, i;
    printf("Enter the position: ");
    scanf("%d", &pos);

    if (pos <= 0 || pos > count + 1) {
        printf("Invalid position\n");
    } else if (pos == count + 1) {
        insertend(count);
    } else if (pos == 1) {
        insertbeg(count);
    } else if (pos >= 2 && pos <= count) {
        newnode = (struct node*)malloc(sizeof(struct node));
        printf("Enter the data: ");
        scanf("%d", &(newnode->data));
        traverse = start;
        for (i = 1; i < pos - 1; i++) {
            traverse = traverse->next;
        }
        newnode->next = traverse->next;
        traverse->next = newnode;
        count++;
    }
    return count;
}

int deletebeg(int count) {
    if (start == NULL) {
        printf("List is empty\n");
    } else if (start->next == start) {
        printf("Deleted item is %d\n", start->data);
        free(start);
        start = NULL;
        count--;
    } else {
        temp = last = start;
        while (last->next != start) {
            last = last->next;
        }
        printf("Deleted item is %d\n", temp->data);
        start = start->next;
        last->next = start;
        free(temp);
        count--;
    }
    return count;
}

int deleteend(int count) {
    if (start == NULL) {
        printf("List is empty\n");
    } else if (start->next == start) {
        printf("Deleted item is %d\n", start->data);
        free(start);
        start = NULL;
        count--;
    } else {
        temp = start;
        while (temp->next != start) {
            last = temp;
            temp = temp->next;
        }
        printf("Deleted item is %d\n", temp->data);
        last->next = start;
        free(temp);
        count--;
    }
    return count;
}

int deletepos(int count) {
    int pos, i;
    printf("Enter the position you want to delete: ");
    scanf("%d", &pos);

    if (start == NULL) {
        printf("List is empty\n");
    } else if (pos <= 0 || pos > count) {
        printf("Invalid position\n");
    } else if (pos == 1) {
        count = deletebeg(count);
    } else if (pos > count + 1) {
        printf("Invalid position\n");
    } else if (pos == count + 1) {
        count = deleteend(count);
    } else if (pos >= 2 && pos <= count) {
        temp = start;
        for (i = 1; i < pos - 1; i++) {
            temp = temp->next;
        }
        nextnode = temp->next;
        printf("Deleted item is %d\n", nextnode->data);
        temp->next = nextnode->next;
        free(nextnode);
        count--;
    }
    return count;
}

void traversing() {
    if (start == NULL) {
        printf("List is empty\n");
    } else {
        traverse = start->next;
        printf("\nData in linked list is %d", start->data);
        while (traverse != start) {
            printf("\nData in linked list is %d", traverse->data);
            traverse = traverse->next;
        }
    }
}

void isfull() {
    newnode = (struct node*)malloc(sizeof(struct node));
    if (newnode == NULL) {
        printf("List is full\n");
    } else {
        printf("List is not full\n");
        free(newnode);
    }
}

void isempty() {
    if (start == NULL) {
        printf("List is empty\n");
    } else {
        printf("List is not empty\n");
    }
}

void searching() {
    int search, f = 0, pos = 1;
    traverse = start;
    printf("Enter the item you want to search: ");
    scanf("%d", &search);
    while (traverse->next != start) {
        if (traverse->data == search) {
            f = 1;
            break;
        }
        traverse = traverse->next;
        pos++;
    }
    if (f == 1) {
        printf("Item is found at %d loc\n", pos);
    } else {
        printf("Item is not found\n");
    }
}


int main() {
    int ch, count = 0;
    while (1) {
        printf("\n1. Insert at beg\n");
        printf("2. Insert at end\n");
        printf("3. Insert at pos\n");
        printf("4. Delete at beg\n");
        printf("5. Delete at end\n");
        printf("6. Delete at pos\n");
        printf("7. Isfull\n");
        printf("8. Isempty\n");
        printf("9. Traversing\n");
        printf("10. Searching\n");
        printf("11. Exit\n");
        printf("Enter your choice: ");
        scanf("%d", &ch);

        switch (ch) {
            case 1:
                count = insertbeg(count);
                break;
            case 2:
                count = insertend(count);
                break;
            case 3:
                count = insertpos(count);
                break;
            case 4:
                count = deletebeg(count);
                break;
            case 5:
                count = deleteend(count);
                break;
            case 6:
                count = deletepos(count);
                break;
            case 7:
                isfull();
                break;
            case 8:
                isempty();
                break;
            case 9:
                traversing();
                break;
            case 10:
                searching();
                break;
            case 11:
                exit(1);
            default:
                printf("Enter the valid data\n");
        }
    }
    return 0;
}


        </pre>
    </div>
<h3>output</h3>
    <div id="div5">
        <pre>

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isfull
8. Isempty
9. Traversing
10. Searching
11. Exit
Enter your choice: 1
Enter the data: 23

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isfull
8. Isempty
9. Traversing
10. Searching
11. Exit
Enter your choice: 2
Enter the data: 34

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isfull
8. Isempty
9. Traversing
10. Searching
11. Exit
Enter your choice: 3
Enter the position: 2
Enter the data: 34

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isfull
8. Isempty
9. Traversing
10. Searching
11. Exit
Enter your choice: 9

Data in linked list is 23
Data in linked list is 34
Data in linked list is 34
1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isfull
8. Isempty
9. Traversing
10. Searching
11. Exit
Enter your choice: 4
Deleted item is 23

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isfull
8. Isempty
9. Traversing
10. Searching
11. Exit
Enter your choice: 5
Deleted item is 34

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isfull
8. Isempty
9. Traversing
10. Searching
11. Exit
Enter your choice: 7
List is not full

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isfull
8. Isempty
9. Traversing
10. Searching
11. Exit
Enter your choice: 8
List is not empty

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isfull
8. Isempty
9. Traversing
10. Searching
11. Exit
Enter your choice: 6
Enter the position you want to delete: 2
Invalid position

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isfull
8. Isempty
9. Traversing
10. Searching
11. Exit
Enter your choice: 11

--------------------------------
</pre>
    </div>
</body>
</html>
