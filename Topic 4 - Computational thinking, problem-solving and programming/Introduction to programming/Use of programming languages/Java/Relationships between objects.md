If we take a relationship like 
<img src="https://i0.wp.com/codecishk.com/wp-content/uploads/2020/09/Screen-Shot-2020-09-20-at-5.39.14-PM.png?w=462&ssl=1">

We can model this with the [[Class]]
```java
public class Listing {

       private String title;

       private boolean active;

       private User author;

       private int price;

       private List<Bid> bids;

       private String id;
   
       public Listing()
       {
     
       }
   
}
```

Where a big is 
```java
public class Bid {
	private String title;
	private boolean active;
	private User author;
	private int price;
	public Bid()
	{
	}
}
```

```java
Bid currentBid = **new** Bid();
bids.add(currentBid);
```