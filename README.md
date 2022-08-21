# Manipulating-Tabular-Data-Using-Pandas
Looking at different techniques to organize and locate data in a DataFrame

The content of this repository is from the book "Python: Machine Learning" by Wei-Meng Lee

In this repository, you can see the use of Pandas to represent tabular data.  I demonstrate the two main Pandas data structures: Series and DataFrame.  I attempted to keep things simple, and show some of the most common operations that would be performed on these data structures.  As extracting rows and columns from DataFrams is so common, the section is summarized is a few areas.

Below is a quick list of common DataFrame Operations:

Extract a range of rows using row numbers                               df[2:4]
                                                                        df.iloc[2:4]

Extract a single row using row number                                   df.iloc[2]

Extract a range of rows and range of columns                            df.iloc[2:4, 1:4]

Extract a range of rows and specific columns using positional values    df.iloc[[2:4, [1,3]]

Extract specific row(s) and column(s)                                   df.iloc[[2,4], [1,3]]

Extract a range of rows using labels                                    df['20910601':'20910601']

Extract a single row based on its label                                 df.loc['20910601']                          

Extract specific row(s) using their labels                              df.loc[[date1,date2]]
                                                                       
Extract specific row(s) and column(s) using their labels                df.loc[[date1, date2], ['A','C']]
                                                                        df.loc[[date1, date2], 'A':'C']]

Extract a range of rows and columns using their labels                  df.loc[[date1:date2, 'A':'C']
