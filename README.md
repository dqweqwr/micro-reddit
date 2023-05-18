Created a version of reddit with lots of missing features in order of practice active record.
only used in the rails console.

planning out data:
-User:
    -username:string required
    -email:string required
    -has_many posts
    -has_many comments

-Post:
    -title:string required
    -body:string required
    -belongs_to user
    -has_many comments

-Comment:
    -body:text required
    -belongs_to user
    -belongs_to post
