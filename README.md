# ASSOCIAÇÃO 

Table Father 
-id
-name

Table Child
-id
-name
-father_id 

>> Terminal do projeto: 

`rails g model Father name`
`rails g model Child name father:references`
