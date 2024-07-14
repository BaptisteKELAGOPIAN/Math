
# MATHS

Une collection de petits projets en Python développés pour illustrer et appliquer divers concepts mathématiques.


Chaque projet a été réalisé dans un délai de deux semaines.


## Usage

Pour executer, les projets il suffit de :

```bash
  $Projectname -h
```


## 301dannon

The project
You’ve been hired by Dannon to sort all the information from their databases. There are a few thousand petabytes of data, and it is critical to implement the most optimal sort possible.

You have to implement and benchmark the following algorithms:

Selection sort
Insertion sort
Bubble sort
Quicksort
Merge sort
To ensure you get the proper results, please follow these implementation guidelines:

Whenever you go through the list of elements (whether you are looking for, selecting or inserting an element), always go from left to right.
For quicksort, always pick the first element as pivot, and keep the relative order of the elements in both partitions.
Don’t optimize the algorithms, or you will skew the results. For example, don’t use a flag to stop bubble sort early when nothing was swapped.

## 302separation 

In 1929, a Hungarian named Frigyes Karinthy established the theory of six degrees of separation: every per-son in the world can be connected to any other person via a chain of individual relationships, that has nomore than six links. Nowadays, social networks makes it easy to evaluate the degree of separation between two individuals, and to test this theory.

Starting with a file that contains a list of friendship links between different Facebook accounts, the goal of this project is to use graph theory to compute the degree of separation between two people.

Your program must display the following:

the list of people in alphabetical order (the order that will be used to build the matrices)
the adjacency matrix
the matrix of the shortest paths, with lengths less than or equal ton.
If two names are given as argument to the program, it must instead display the degree of separation be-tween those two people, or -1 if they are not connected.

## 305construction

In the construction industry, the foreman is the person who manages, among other things, the scheduling of a construction site, and plans when contractors are intervening (which can be frequently). In order to do this, he uses software to automate the scheduling.

You must create a project management software that helps organize construction, based on the MPM method. Starting from a file that describes all of the project tasks, you have to display the following:

Total duration of construction
The earliest and latest start dates for each task
A Gantt chart that specifies intervals of fluctuation

## 308reedpipes

The project
Having been a reed pipe enthusiast for a long time now, your cousin cobbled together a little numerically controlled machine that will enable him to carry out a serial production of reed pipes and make a business out of it. However, he would like a software so that he can design his pipes himself...

So, you have to create a program for him that, starting from the pipe’s radius (in cm) with abscissas 0, 5, 10, 15 and 20cm, and using cubic splines, displays the radii of n points that are evenly distributed along the pipe. In order to simplify the debugging process, you will also display the resolved linear system’s vector result in order to obtain the spline.

## 309pollution

The project
The ambient air quality monitoring in France is ensured by independent associations, members of the ATMO federation, and, on behalf of the State and public authorities, are responsible for implementing means of monitoring.

Why not you? The Lozère market seems easily open for the taking...

So, you decide to start a project based on collaborative initiatives like Citoyens Capteurs in order to acquire data. All that’s left to do is to create a little software for viewing the data...

You receive the data in triplets (x, y, p) where x and y are the coordinates (presumably integers so it’s simpler) on a normal grid and p the pollution level (in percentage). We will consider that the pollution is non-existent on the grid’s other points.

Your program will use Bézier surfaces to smooth out the data and display the value of the pollution level ina point inside the observed area.