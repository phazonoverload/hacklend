# HackLend :purple_heart:

## The problem

Hackathon (and other tech event) organizers often purchase lots of items which are reusable. These are often only ever used during events. Meanwhile, other organizing teams may go ahead and purchase the same items for their events. 

## The solution

HackLend is a community-curated list of items which organizers are happy to lend to one another. Organizers should feel free to look at the list and get in touch with owners and ask to borrow their kit. This can help team save money, and make more use of kit which has been bought by others. 

## Adding your own kit

1. Fork this repository into your own account
2. Edit data.js (you can do this from within GitHub's online interface) and add a new object for each item. This is everything in between the `{` and `}` brackets. Make sure there's a comma between each object.
3. Submit a pull request to the origin repo (phazonoverload/hacklend)

### Your contribution 

Your contribution should look like this:

#### Before

<pre>
var items = [
  {
    name: "Name of item",
    link: "http://amazon.co.uk/LINK_TO_ITEM",
    owner: "Team/person name",
    location: "City and country",
    contact: "name@example.com"
  }
];
</pre>

### After

<pre>
var items = [
  {
    name: "Name of item",
    link: "http://amazon.co.uk/LINK_TO_ITEM",
    owner: "Team/person name",
    location: "City and country",
    contact: "name@example.com"
  }<b>,
  {
    name: "Name of item",
    link: "http://amazon.co.uk/LINK_TO_ITEM",
    owner: "Team/person name",
    location: "City and country",
    contact: "name@example.com"
  }</b>
];
</pre>

Please make sure each of your items is separate.

---

## The rules (and disclaimers)

* I accept no responsibility for loss or damage. Everyone who has contributed items to this project does so at their own risk, and should try to ensure borrowers are reputable.
* You should agree a return date for kit if you are lending it.
* If you borrow kit, it's reasonable to expect the lender to ask for the cost of postage.
* This is not intended for rentals. If anyone asks for money in return for their kit, you should let me know immediately.
* No one is obligated to lend you things. It is completely ok for them to say no. If someone becomes harassing, you should let me know.
