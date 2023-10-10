![image](https://github.com/nlbse2024/code-comment-classification/assets/5877721/81d6ec3c-3b8b-41e5-b5b8-93dac50c68bd)# Extended version of Java dataset

`merged_java.csv` contains an extended version of the Java dataset.
The manually classified Java comments present in "Classifying code comments in Java open-source software systems" have been merged with the NLBSE'23 Tool Competition Java dataset.
A conservative approach has been adopted to remove duplicates during the merging process, in particular, given only an overlap in files of 10%. Those files have been removed from the newly considered dataset. This approach also leaves the original NLBSE'23 Tool Competition Java dataset untouched.

`partition_split.csv` is a different representation of the above dataset. In particular, it follows the classification strategy used in the NLBSE'23 Tool Competition Java dataset with positive and negative instances, each split into train and test. See columns `instance_type` and `partition`.
