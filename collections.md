

#### Collection
* A collection is a framework that provide readymade archetecture to store and manipulate the objects.

#### Collection Library
* java.utils

#### Structure
* iIterator extents iCollection extends iList implements cArrayList, cLinkedList, cVector extends cStack
* iIterator extents iCollection extends iQueue extends DeQueur implements priorityQueue, ArrayDequeue
* iIterator extents iCollection extends Set  extends SortedSet impements HashSet, LinkedHashSet, TreeSet

#### Methods of Collections Interface
* boolean add(E e); boolean addAll(Collection<E> e); remove(E e); removeAll(E e); int size(); void clear(), boolean contains(E e); boolean containsAll(Collection<?>);Collections.reverse(E e); Collections.sort();  Collections.unmodifiableList(E e)
Iterator iterator(); Object[] toArray(); boolean isEmplty(); parallelStream(); stream(); splitIterator(); boolean equals(); int hashCode();

#### Methods of Iterator
* boolean hasNext(); Object next(); void remove();

#### List Interface
* List <data-type> list1= new ArrayList();  
* List <data-type> list2 = new LinkedList();  
* List <data-type> list3 = new Vector();  
* List <data-type> list4 = new Stack();  

#### ArrayList
* It uses a dynamic array to store the duplicate element of different data types
* The ArrayList class maintains the insertion order and is non-synchronized.
* ArrayList class can be randomly accessed.
* Link [https://www.javatpoint.com/java-arraylist]
* ArrayList provides constant time for search operation
  * __Methods__ : void add(int index, E element); void clear(); E get(int index), listIterator(); int lastIndexOf(Object o); int indexOf(Object o);
E remove(int index); boolean remove(Object o); removeRange(int fromIndex, int toIndex); E set(int index, E element); void sort(Comparator<? super E> c);
List<E> subList(int fromIndex, int toIndex); int size()

#### LinkedList
* It uses a doubly linked list internally to store the elements
* It can store the duplicate elements.
* It maintains the insertion order and is not synchronized.
* In LinkedList, the manipulation is fast because no shifting is required.
* The LinkedList provides constant time for add and remove operations. So it is better to use LinkedList for manipulation.
#### Vector
* It is similar to ArrayList
* It is synchronized and contains many methods that are not the part of Collection framework
#### Stack
* It implements the last-in-first-out data structure,
* he stack contains all of the methods of Vector class and also provides its methods like boolean push(), boolean peek(), boolean push(object o)

#### Queue Interface
* Queue interface maintains the first-in-first-out order
* Queue<String> q1 = new PriorityQueue();  
* Queue<String> q2 = new ArrayDeque(); 
#### Priority Queue
* It holds the elements or objects which are to be processed by their priorities
* PriorityQueue doesn't allow null values to be stored in the queue, element()

#### Deque Interface
* In Deque, we can remove and add the elements from both the side
* Deque stands for a double-ended queue which enables us to perform the operations at both the ends.
* Deque d = new ArrayDeque();  

#### ArrayDeque
* Unlike queue, we can add or delete the elements from both the ends.
* ArrayDeque is faster than ArrayList and Stack and has no capacity restrictions.

#### Set Interface
* Set<data-type> s1 = new HashSet<data-type>();  
* Set<data-type> s2 = new LinkedHashSet<data-type>();  
* Set<data-type> s3 = new TreeSet<data-type>(); 
#### HashSet
*  It represents the collection that uses a hash table for storage
* Hashing is used to store the elements in the HashSet. 
* It contains unique items.
#### LinkedHashSet
* It maintains the insertion order and permits null elements.
#### SortedSet Interface
* The elements of the SortedSet are arranged in the increasing (ascending) order. 
* The SortedSet provides the additional methods that inhibit the natural ordering of the elements.
* SortedSet<data-type> set = new TreeSet(); 
#### TreeSet
* Like HashSet, TreeSet also contains unique elements.
* However, the access and retrieval time of TreeSet is quite fast. 
* The elements in TreeSet stored in ascending order.
