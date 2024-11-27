# Election_management
A Java-based GUI application for managing the election process. The system enables administrators to manage voters and leaders, conduct voting, view results, and handle deleted data with a trash feature. It uses Swing for the graphical interface and integrates various data structures like Binary Search Tree (BST), HashMap, and Stack for efficient management.
Features:
Voter Management:
Add, update, and view voters using a Binary Search Tree (BST).
Store voter information such as name, ID, address, age, and mobile number.
Track voting status (whether a voter has voted).

Leader Management:
Add, update, delete, and restore leaders.
Store leader details such as ID, name, party, taluka, district, and party image.
Deleted leaders are temporarily stored in a trash stack.

Voting Process:
Voters can cast votes for leaders from their district and taluka.
Voting is restricted to ensure voters can only vote once.

Results and Re-Elections:
View leader-wise, party-wise, and taluka-wise election results.
In case of a tie, re-election is required for leaders or parties.
Automatically reset votes for re-elections in case of a tie.

Trash Functionality:
Manage deleted leaders with the ability to restore them or permanently remove from trash.

Prerequisites:
Java Development Kit (JDK) 8 or higher.
An IDE like IntelliJ IDEA, Eclipse, or NetBeans.
Swing library (pre-included with Java).
