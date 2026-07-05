# Match-Making-System
The system allows users to register (as normal or premium users), set preferences (desired gender, age range, city), and find compatible matches through an automated compatibility scoring algorithm. The data is persisted to plain-text files so that information survives between sessions.

This project demonstrates a complete, working application of core OOP principles in C++. The Matchmaking System successfully implements all four pillars of OOP:

•Encapsulation through private members and controlled access via getters/setters.
•Inheritance through the User/PremiumUser hierarchy establishing an IS-A relationship.
•Polymorphism through virtual method dispatch over a vector<User*> at runtime.
•Abstraction through interface-driven design with pure virtual methods and utility classes.

The architecture cleanly separates concerns across 7 well-defined classes, making the codebase modular, extensible, and maintainable. The system is fully functional with file persistence, dynamic match scoring, and a complete menu-driven interface.
