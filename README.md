## Matplotlib-Challenge

Observations and conclusions:

Description of the Dataset:

    - Data evaluates the effectiveness of 10 drug regimens on reducing tumors in mice

    - Experiment conducted across 249 mice and sampled tumor and mouse data at various timepoints after injection

    - Total data included 1893 timempoints; avg 7.6 per mouse across all mice; range from 6 - 9.2 per mouse by regimen

    - Population of mice were evenly split between male and female
    
Data observations:

    - Two drugs appeared to be the most effective -- Ramicane and Capomulin -- based on the average final tumor size

    - Three other drugs -- Propriva, Cefatmin, and Infubinol -- also appeared to have some positive effect realtive to the rest of the group, although it's not clear whether it's a statistically significantly better effect than the rest of the drugs

     - There was a strong positive correlation between mouse weight and tumor size, which makes sense, as we would expect mice with smaller tumors to weigh less than mice with larger tumors, all else equal
        
Further analysis that could be conducted:

    - I'm assuming the sex of the mice were equally distributed across the various regimens -- roughly 5 male and 5 female mice per regimen, and thus sex had no impact on individual treatments

    - However, it would be interesting to see whether the effectiveness of all treatments varied acoss the sexes, and could look at the how the effectiveness varied by treatment and accross all treatments

    - Similar analysis could be performed looking at mouse age


Log:
7/20:
- Analysis complete, all charts formatted correctly and producing correct output

7/18:
- Had difficultly determing the final tumor value based on time and merging with the clean dataset as suggested by directions
- I used what I think is a simpler approach to sort the data by timepoints in ascending order and then using the drop duplicates function by Mouse ID to keep the last Mouse ID on the last timepoint, which also produces the final tumor volume

7/17:
- Calculated data to plot mice per regimen and male / female ratios
- Created bar charts

7/16:
- Created clean data file removing duplicate mouse IDs and timepoints 
- Caldulated and framed summary statistics