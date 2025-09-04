# LAb_BDpelis

drop schema if exists Movies;
create schema Movies;
use Movies;

create table pelis(
id int auto_increment,
title varchar (100) not null,
star varchar(100),
genre varchar (70),
release_year year,
sales int,
primary key (id)
);

insert into pelis (title, star, genre, release_year, sales) values
('The Shawshank Redemption', 'Tim Robbins', 'Drama', 1994, 28313053),
('Django Unchained', 'Jamie Foxx', 'Western',2012, 449841566),
('Shutter Island', 'Leonardo Dicaprio','Thriller/Suspense', 2010, 299461782),
('The Departed', 'Jack Nicholson', 'Drama', 2006, 289660619),
('The Green Mile', 'Tom Hanks', 'Drama', 1999, 290701374);
