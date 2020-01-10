# Assignment 3

## Setting up

### Cloning
You should be pulling from gitlab from `https://gitlab.com/dawsoncollege/php/f2018/section2/project3-stockportfolio/team1/ass3.git`.
Otherwise, you can view the public website [HERE](https://stockxportfolio.herokuapp.com/)

### Setting up Laravel
1. ssh into vagrant and cd to `/code/ass3/`.
2. rename the file `.env.example` to `.env`
3. run the command `composer update`
4. If you MODIFY the database, you NEED to do: 
    1. `php artisan migrate:rollback`
    2. `php artisan migrate` 



