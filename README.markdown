# Rails basic auth generator

This is a generator for the code used in my [rails authentication tutorial](http://www.aidanf.net/rails_user_authentication_tutorial).

This generator creates a basic user authentication system

#### Included:
* a User model which uses sha1 encryption for passwords
* a Controller with signup, login, forgot_password and logout actions
* a Mailer for sending forgotten passwords
* a migration for creating the user table
* unit and functional tests
            
#### Example

    ./script/generate login user

#### More info
	
http://www.aidanf.net/rails_user_authentication_tutorial
	
