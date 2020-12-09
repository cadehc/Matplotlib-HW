Matplotlib HW
*all work done in Jupyter*
Jupyter Link: 
http://localhost:8888/notebooks/Documents/databootcamp-material/rice-hou-data-pt-10-2020-u-c/Homework/05-Matplotlib/Instructions/Pymaceuticals/pymaceuticals_matplotlib.ipynb#Bar-and-Pie-Charts

Observations:
	1. My first major observation from this data has to do with which drugs were the most effective in terms of the average
	final tumor volume. Capomulin and Ramicane seem to be the most effective drugs with an average final volume of 40.68
	and 40.22. All other drugs had a final avergae volume above 52mm3, with the highest being Ketapril at 55.24mm3.
	However, Ketapril had the highest variance in final tumor volume at 68.19.
	
	2. When looking at the box plot for Capomulin, Ramicane, Infubinol and Ceftamin, we can see that Infubinol and Ceftamin
	were, overall, not nearly as effective in this trial. Their quartile numbers were higher, especially Infubinol, which did
	not have much variance in tumor volume. This suggests that Infubinol is not likely to have a result anymore near the 
	numbers of Capomulin or Ramicane.
	
	3. Finally, when we compare tumor volume with the timepoint of Capomulin on Mouse ID "s185", we notice that the drug's 
	most effective period is between timepoints 5 and 10. This period has the steepest decline in tumor volume with a total
	reduction of about 6.2mm3. However, it's least effective timepoint is immediately after, from timepoints 10 to 15,
	where the tumor actually grew 0.5mm3. This is the only occurance of tumor growth in the Capomulin data, but without
	more data, there's really no way to tell what caused it.