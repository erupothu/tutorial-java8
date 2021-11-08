

#### Collection
  * A collection is a framework that provide readymade archetecture to store and manipulate the objects.

#### Collection Library
  * java.utils

#### Structure
  * iIterator extents iCollection extends iList implements cArrayList, cLinkedList, cVector extends cStack
  * iIterator extents iCollection extends iQueue extends DeQueur implements priorityQueue, ArrayDequeue
  * iIterator extents iCollection extends Set  extends SortedSet impements HashSet, LinkedHashSet, TreeSet

#### Methods of Cikkections Interface
  * boolean add(E e); boolean addAll(Collection<E> e); remove(E e); removeAll(E e); int size(); void clear(), boolean contains(E e); boolean containsAll(Collection<?>);
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

#### LinkedList
  * It uses a doubly linked list internally to store the elements
  * It can store the duplicate elements.
  * It maintains the insertion order and is not synchronized.
  * In LinkedList, the manipulation is fast because no shifting is required.
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
