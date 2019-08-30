# Corva Python Test Task

Thank you for applying to Corva! We'd like to see how you solve problems with large datasets in a performant way.

## Dataset Input
Provided in `data/movies.json` is a list of IMDB movies since 1900. Each movie should have a release year, and will sometimes have a cast list.

Example data node:
```
{
    "title": "Open Season",
    "year": 2006,
    "cast": [
      "Martin Lawrence",
      "Ashton Kutcher",
      "Debra Messing",
      "Gary Sinise"
    ],
    "genres": [
      "Animated"
    ]
  }
```

## Data Processing

Your goal is to process this file and output a list of 3 columns:

1. Cast Name
2. Year
3. Sum count of movies the cast member starred in that year

The dataset should be sorted primarily alphabetically in ascending order by Cast Name, and secondly numerically in ascending order by Year.

## Dataset Output
Please output data separated by either commas or semicolons.

Example output format (note, this may not be accurate years and numbers):

```
Ashton Kutcher,2006,2
Ashton Kutcher,2007,1
Gary Sinise,2005,3
Gary Sinise,2006,4
``` 

## Deliverables
Your deliverable should be a solution written in Python 3 that can be run with a single command and that outputs to stdout. Don't email or commit any output files to source control. Any dependencies should be defined in a requirements.txt file. 

A good solution will be readable, maintainable, and performant, so please write this code like you would expect it to exist in a production environment for 5+ years.

For extra credit, you can come up with a process to remove invalid cast member names from the output.

Good luck!