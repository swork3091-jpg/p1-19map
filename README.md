date 03/09/26
day 02
p1-19

HashMap, LinkedHashMap, TreeMap, keys/values, map patterns.Frequency counter and lookup exercises.

javamaps 
1.Hashmap
2.Linkedhashmap
3.Treemap

1.Hashmap 
hashmap is the general-purpose choice when you don't care about ordering.

map.put("apple",3);
map.put("banana",5):
map.put("orange",2):
sout(map.get("banana"));

//5

2.linkedhashmap
it's maintain insertion order.

map.put("apple", 3);
map.put("banana", 5);
map.put("orange", 2);

for (String key : map.keySet()) {
    System.out.println(key);
}

output:
apple 
banana
orange

3.treemap
treemap keeps keys sorted.

map.put("orange", 2);
map.put("apple", 3);
map.put("banana", 5);

System.out.println(map);

output:
{apple=3, banana=5,orange=2}

4.key nd values
Map<String, Integer> marks = new HashMap<>();

marks.put("Rahul", 90);
marks.put("Amit", 80);
marks.put("Priya", 95);

key = Rahul
value = 90

5.map patterns
map pattern means a common way of using a map to solve coding problems

int[] nums = {2,3,2,5,3,2};

means ketli var repeat thai e element e jovanu che 
2 ~ 3
3 ~ 2
5 ~ 1















