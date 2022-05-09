SinglyLinkedListNode* deleteNode(SinglyLinkedListNode* llist, int position) {
    if((position) == 0) {
        return llist->next;
    }
    llist->next = deleteNode(llist->next, position-1);
    return llist;
}
