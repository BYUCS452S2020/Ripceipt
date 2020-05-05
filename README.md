# Ripceipt
Store data from customer's purchases and organize it to make it accessible in a helpful way

### Rest in pieces, receipts!  

---

#### Project Description
Ripceipt is better at organizing your receipts than the shoebox under your bed. Use it instead of holding onto old, smudged pieces of paper and let it intelligently record your purchases so you can be smarter with your finances.

Users will be able to add receipts through manual input or with a Ripceipt Printer at a merchant near you (printer hardware & software development is out of the scope of this project).

Their data will be kept secure, locally on device, and made available in the app for helpful analysis. Design personal budgets, set spending limits, the possibilities are endless!

A MVP already exists, but our data storage and analytic tools exist on the scale between non-existent and very messily unhelpful.

#### Team

I'm looking for anyone who would like to join our already existing team for the purposes of this project. No business equity is awarded or will result from the efforts of team members.

#### Technical

- SQL:
    MySQL will be used for the relational database implementation.

- NoSQL:
    [Sembast](https://pub.dev/packages/sembast) is the NoSQL database we will use to store data locally on-device. We will explore the scalability of the Flutter package and if this implementation is not performant enough, we will use a remote MongoDB instance.

- Other:
    The application is built in Flutter, so any experience with cross-platform mobile development or Dart is welcome.
    
    Objectives: 
    1. Organize receipt data in a productive manner
    2. Display the data in descriptive, dynamic graphs
    3. Build infrastructure for backing up receipt data to our own data center or services such as Dropbox/Google Drive/Box

#### Business
    
The app is free to use for all Android and iOS users with no ads. Revenue is generated monthly from businesses who use the Ripceipt printer to provide customers with receipts at their location.

#### Legal

Ripceipt is registered as an LLC.
