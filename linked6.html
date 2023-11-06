


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
    char str[10];
    struct node *next;
};

struct node *start = NULL, *last = NULL, *newnode, *temp, *traverse, *ptr, *previous, *nextnode;


int insertbeg(int count) {
    if (start == NULL) {
        newnode = (struct node *)malloc(sizeof(struct node));
        printf("Enter the string: ");
        scanf("%9s", newnode->str);
        start = last = newnode;
        last->next = start;
        count++;
    } else {
        newnode = (struct node *)malloc(sizeof(struct node));
        printf("Enter the string: ");
        scanf("%9s", newnode->str);
        newnode->next = start;
        start = newnode;
        last->next = start;
        count++;
    }
    return count;
}

int insertend(int count) {
    if (start == NULL) {
        newnode = (struct node *)malloc(sizeof(struct node));
        printf("Enter the string: ");
        scanf("%9s", newnode->str);
        start = newnode;
        newnode->next = start;
        count++;
    } else {
        newnode = (struct node *)malloc(sizeof(struct node));
        printf("Enter the string: ");
        scanf("%9s", newnode->str);
        last = start;
        while (last->next != start) {
            last = last->next;
        }
        last->next = newnode;
        newnode->next = start;
        count++;
    }
    return count;
}

int insertpos(int count) {
    int pos, i;
    printf("Enter the position: ");
    scanf("%d", &pos);

    if (pos <= 0 || pos > count + 1) {
        printf("Invalid position\n");
    } else if (pos == 1) {
        count = insertbeg(count);
    } else if (pos == count + 1) {
        count = insertend(count);
    } else if (pos >= 2 && pos <= count) {
        newnode = (struct node *)malloc(sizeof(struct node));
        printf("Enter the string: ");
        scanf("%9s", newnode->str);
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
        printf("Deleted string is %s\n", start->str);
        free(start);
        start = NULL;
        count--;
    } else {
        temp = last = start;
        printf("Deleted string is %s\n", temp->str);
        while (last->next != start) {
            last = last->next;
        }
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
        printf("Deleted string is %s\n", start->str);
        free(start);
        start = NULL;
        count--;
    } else {
        temp = start;
        while (temp->next != start) {
            last = temp;
            temp = temp->next;
        }
        printf("Deleted string is %s\n", temp->str);
        last->next = start;
        free(temp);
        count--;
    }
    return count;
}

int deletepos(int count) {
    int pos, i;
    printf("Enter the position: ");
    scanf("%d", &pos);

    if (start == NULL) {
        printf("List is empty\n");
    } else if (pos <= 0 || pos > count) {
        printf("Invalid position\n");
    } else if (pos == 1) {
        count = deletebeg(count);
    } else if (pos == count) {
        count = deleteend(count);
    } else if (pos >= 2 && pos < count) {
        traverse = start;
        for (i = 1; i < pos - 1; i++) {
            traverse = traverse->next;
        }
        temp = traverse->next;
        printf("Deleted string is %s\n", temp->str);
        traverse->next = temp->next;
        free(temp);
        count--;
    }
    return count;
}

void traversing() {
    if (start == NULL) {
        printf("List is empty\n");
    } else {
        traverse = start->next;
        printf("\nString in linked list is %s", start->str);
        while (traverse != start) {
            printf("\nString in linked list is %s", traverse->str);
            traverse = traverse->next;
        }
    }
}

void isfull() {
    newnode = (struct node *)malloc(sizeof(struct node));
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
    char search[10];
    int f = 0, pos = 1;
    traverse = start;
    printf("Enter the string you want to search: ");
    scanf("%9s", search);
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
                exit(0);
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
7. Isempty
8. Isfull
9. Display
10. Searching
11. Exit
Enter your choice
1
Enter the string: ss

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isempty
8. Isfull
9. Display
10. Searching
11. Exit
Enter your choice
2
Enter the string: dd

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isempty
8. Isfull
9. Display
10. Searching
11. Exit
Enter your choice
3
Enter the position: 1
Enter the string: aaa

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isempty
8. Isfull
9. Display
10. Searching
11. Exit
Enter your choice
8
List is not full

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isempty
8. Isfull
9. Display
10. Searching
11. Exit
Enter your choice
7

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isempty
8. Isfull
9. Display
10. Searching
11. Exit
Enter your choice
4
Deleted string is aaa

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isempty
8. Isfull
9. Display
10. Searching
11. Exit
Enter your choice
5
Deleted string is dd

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isempty
8. Isfull
9. Display
10. Searching
11. Exit
Enter your choice
6
Enter the position you want to delete: 1
Deleted string is ss

1. Insert at beg
2. Insert at end
3. Insert at pos
4. Delete at beg
5. Delete at end
6. Delete at pos
7. Isempty
8. Isfull
9. Display
10. Searching
11. Exit
Enter your choice
11

--------------------------------
</pre>
    </div>
</body>
</html>
