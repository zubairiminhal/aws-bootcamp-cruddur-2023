# Week 0 — Billing and Architecture'

# Week 0

### **Monolithic Architecture:**



The Iron Triangle is a model to where is (You can only have 2 of the three things, choose what you want LOL), you can keep it as: Cheap, Fast and Good! Say, if you want it to be cheap, you will have to sacrifice it being fast or maybe good.. and so on.. [Chris Williams]



### **Notes to self (after understanding all the requirements):**



### **Recap:**



You need to understand the framework that the investors are expecting and the marketing team is expecting and the business is actually needing it

## **Architecture**

### What is a good architecture?

1. Requirements - Something that the project must achieve at the end (Crudder - Ephemeral and looks like Twitter)



1. Risk - can prevent the project from being successful (must be mitigated) 
    1. SPoF (Single Point of Failures) - If you need 100% uptime, and have multiple SPoFs you need to mitigate that
    2. User Commitment
    3. Delivery Timeline 
    
    You can relate them to Iron Triangle (fast, cheap and good)
    
2. Assumptions - are factors held as true for the planning & implementation phases 
    1. Sufficient Network Bandwidth (for twitter)
    2. Stakeholders will be available to make decisions
    3. Budget is approved 🙂 
3. Constraints
    1. Time (14 weeks)
    2. Budget (0$)
    3. Vendor Selection (AWS)

Once we have gathered the RRACs, you can actually now start creating designs

1. Conceptual Design - Not a technical design; also called as Napkin Designs 
2. Logical Design - zooms in to lower layer framework and breaks out to large conceptual blocks; called as blueprint
3. Physical Design - Actual physical representation of the actual thing



***BONUS POINTS FOR NAPKIN DESIGNS @Minhal Zubairi*** 

### It’s important to Develop a Common Dictionary

- Ask “dumb questions” - why are we here, what is the purpose of this meeting - most people are afraid to ask them
- Play be-the-packet - be the end-user of the application you are building.. it helps you learn a lot about RRACs
- Document everything*

### AWS Well-Architected Framework



**Napkin Designs -**

You have an idea and you want to explain it to your friends or an investor and you will architect it on a Napkin.. there you do not have to be too technical but you have to be logical and confident and straightforward (simple) in the solution you are providing, there is no hard rules what to add in there but it just need to make sense

**Parting note:** 

- Remember the Iron Triangle
- Keep asking Why Why Why, Why are you doing certain things and all
- Keep asking the dumb questions
