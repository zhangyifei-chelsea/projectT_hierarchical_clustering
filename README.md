# Fall20-CS289-Project-T   Hierarchical Clustering
Authors: Zeqing Jin, Yifei Zhang, Xianlin Shao, Zilan Zhang  
University of California, Berkeley   
{zjin2017, yifei_zhang, shayd, shilan}[at]berkeley[dot]edu   

## Repository Structure

This project contains the designed slide, notes, quiz, coding assignment, and the corresponding solution for hierarchical clustering topic of a proposed course 16ML.

The project structure is as follows:

    .
    ├── ...
    ├── coding assignment                                # Folder containing coding assignment
    │   ├── citibike-tripdata.zip                        # Bikesharing dataset for Part4
    │   ├── hierarchical_clustering_assignment.ipynb     # Coding assignment
    │   ├── hierarchical_clustering_solutions.ipynb      # Solution for coding assignment
    │   └── signal.pkl                                   # Singal dataset for Part4
    ├── notes.pdf                                        # Notes introducing the theory of hierarchical clustering
    ├── quiz.pdf                                         # Simple Q&A questions examining students' understanding towards basic concepts
    └── SlideDeck.pdf                                    # A summary of notes

## Project Summary and Learning Objective
Hierarchical clustering is a general family of clustering algorithms that build clusters by merging or splitting them successively. An integrated course notes and corresponding coding assignment about hierarchical clustering will be given, which suit students who have taken or are taking alongside EECS16B and CS61B at UCB. After learning the notes and completing the assignment, students should be able to achieve the following learning objectives:
- Notes:
	-  Know and understand the definition of hierarchical clustering.
	-  Explain theoretically how hierarchical clustering is different from k-means clustering.
	- Read and plot the dendrogram of hierarchical clustering, and explain the merging or splitting process via the dendrogram.
	- Understand the theory of agglomerative hierarchical clustering, and analysize the corresponding dendrogram.
-  Coding Assignment:
	- Part 1: Demo. In this part, students will go over several demos of hierarchical clustering and k-means clustering. From this part, student can have a clearer understanding of how hierarchical clustering and k-means clustering differs. 
	- Part 2: Implementation. In this part, students will implement and visualize agglomeritive and divisive clustering. From this part, students can 
		- Be more familiar with how these algorithm works step by step; 
		- Be more familiar with using numpy and coding with python
	- Part 3: Hyperparameter tuning. In this part, students will directly use sklearn agglomerative function to do clustering on various toy exampls. This is more similar to the real working environment. From this part, students can
		- Be familiar with the differences between different linkage functions
		- Learn to choose the correct distance metric
	- Part 4: Application. This part contains two practical examples, signal clustering and bikesharing station clustering. As for signal clustering, students can
		- Recap the signal correlation covered in EECS16A APS lab
		- Apply agglomerative clustering with self-defined dissimilarity metric with both sklearn AggomerativeClustering and scipy linkage function
		- Learn to choose the best number of clusters k from the dendrogram   
	  As for bikesharing system station clustering, students can work in a senario similar to what data scientists or machine learning algorithm engineers work on. From this process, students can
		- Reinforce their knowledge in EDA and visualization that are covered in previous sections of 16ML
		- Design dissimilarity metric based on real setting
