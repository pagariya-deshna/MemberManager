In this java project I have tried to create a command line application for managing list of members with their details like mobile number, name,course and fees.
Also it includes functionalities like add,update,remove a member,getAll,getByCourse and getByContactNumber.
Project uses file I/O through RandomAccessFile i.e. file handling  to store and retrieve member information from data file 'member.data'.
Usage:
to add new member - java MemberManager add mobile_number name course fee
to get all member - java MemberManager getAll
                  - java MemberManager getByContactNumber mobile_number
                  - java MemberManager getByCourse course_name
to remove member  - java MemberManager remove mobile_number
to update data    - java MemberManager update mobile_number name course fee   
