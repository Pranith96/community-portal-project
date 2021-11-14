
create database community_portal;

use community_portal;

 create table User (
       user_id integer not null auto_increment,
        city varchar(255),
        colony_name varchar(255),
        company_name varchar(255),
        country varchar(255),
        email_id varchar(255) not null unique,
        first_name varchar(255),
        gender varchar(255),
        last_name varchar(255),
        mobile_number bigint,
        password varchar(255) not null,
        plot_no varchar(255),
        user_role varchar(255),
        state varchar(255),
        street_no varchar(255),
        primary key (user_id)
    )
	
	
insert into User (user_id,city, colony_name, company_name, country, email_id, first_name, gender, last_name, mobile_number, password, plot_no, user_role, state, street_no)
    values
        (4,'US', 'qwer', 'NYC', 'india', 'xxxxxxxxxxxxxxxxxxxx@gmail.com','Ravi', 'MALE', 'Ram', '123456789', '12345678', '12', 'ADMIN', 'qwe', '12');
	
