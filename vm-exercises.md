# Virtual Machine (VM) Exercises

## 1st VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder. MAC: done

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-1-intial.twbx` or `ex-1-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course. MAC: done
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-1-sol.twbx` or `ex-1-sol.pbix`. MAC: done

#### Learning Objective

- Edit M-code for data query transformations to provide the desired output of the Query Process using the Advanced Editor.

#### Motivation

- Know about the underlying M-code beneath Power Query transformations. 
- Know about Advanced Editor tool in order to view and edit M-code.
- Learn how to edit M-code with the Advanced Editor to modify parameters which affect the whole Query Process.
- See the results for a sample query column name modification.

#### Steps to be executed by the student (max 6)

- Load Power BI Report ex-1-initial.pbix with pre-processed queries.
- Check the different Applied Steps and parameters for Salesperson query in the Query Settings menu.
- Open the Advanced Editor from the ‘View’ ribbon menu in the Power Query Editor.
- Observe the relation between Applied Steps in the Query Settings menu and the M-code commands.
- Rename ‘Salesperson’ column to ‘EmployeeName’, editing the corresponding ‘#”Merged Columns”’ M-code command in the Advanced Editor.

#### End goal:

![ex1_endGoal](https://github.com/macuguero/sme-bi-course-application/blob/dev_macuguero/ex1.png)


## 2nd VM Exercise

#### Dataset

- [ ] Add datasets used to the `datasets/` folder. MAC: done

#### Files

- [ ] **Initial**: Add file to the `exercises/`  folder with the name `ex-2-intial.twbx` or `ex-2-intial.pbix`, depending if you are auditioning for a Tableau or Power BI course. MAC: done
- [ ] **Solution**: Add file to the `exercises/`  folder with the name `ex-2-sol.twbx` or `ex-2-sol.pbix`. MAC: done

#### Learning Objective

- Correcting errors occurring in the Query Process by editing the query M-code with the Advanced Editor.

#### Motivation

- Learn how errors may occur when inserting data transformations with the Power Query Editor.
- Know how to identify occurring errors and their correspondence with the M-code.
- Learn how to edit M-code with the Advanced Editor in order to solve occurring errors.
- Check how the applied modifications in the M-code provide a corrected Query Process without errors.

#### Steps to be executed by the student (max 6)

*Each bulleted instruction is a complete sentence that describes a specific task.*

- Open the Advanced Editor in the ‘View’ ribbon menu and rename ‘Merged’ column to ‘TitleAbbreviation’ in the ‘#”Merged Columns1”’ M-code command. 
- Check how an error occurs when selecting the ‘Reordered Columns’ step in the Query Settings menu.
- Open the Advanced Editor and rename ‘Merged’ column to ‘TitleAbbreviation’ in the ‘#”Reordered Columns”’ M-code command.
- Check how the former error is corrected when selecting the ‘Reordered Columns’ step in the Query Settings menu, and the column ‘TitleAbbreviation’ appears correctly in the query.

#### End goal:

![ex2_endGoal](https://github.com/macuguero/sme-bi-course-application/blob/dev_macuguero/ex2.png)


