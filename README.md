# CS3SY26_ProjectProposal by Aline Teresa Mendoza from CS Unit of PSHS


## Project Proposal Template:

### Project Title or Name of the Application	: Phenotypic and Genotypic Ratio Predictor For Mendelian Inheritance
### Section			   	      : Sodium
### Group Members			    : Damian Gallarte, Carl De Ramos, Hyacinth Dondo
### Date (Proposal Date)  : Nov 13, 2026

### Project Description:

- A brief summary of the project description and the need for it.

The Phenotypic and Genotypic Ratio Predictor For Mendelian Inheritance is a tool used to automate and visualize the predictions for the genotypic and phenotypic ratios of offspring. This uses Mendel's Laws of segregation and independent assortment and applies logic from Punnett squares, taking the genotypes of parents to generate the probability and outcomes of monohybrid, dihybrid, and multihybrid crosses.

- Describes system components, features, and expected outputs clearly and logically. NOTE: Clearly described the elements(classes), their attributes and methods and how they will interact with each other.

Parent class: 
1. parent_genotype (str): this is the combination of alleles in a parent that will be used in crossing genes
2. 

Allele class:
1. letter (str): the literal letter symbol for a certain allele
2. dominance (boolean): this determines if a certain allele is dominant or recessive.

Genes class:
1. phenotype (list): list of possible traits.
2. observable_traits(): this function returns the 

Genotype class:
1. child_genotype (str): this is one of the possible combinations from the crossing of the parents.
2. genotypic_probability(): this function provides the probability of getting an offspring with the exact child_genotype among all possibilities.

- Include the description as well of your target demographics as the user of your application.

The target demographic and user of this application are high school students around Grade 9 or younger that can benefit from being able to play around with different parent genotypes to see how it affects the phenotypic and genotypic ratio of the offspring. This can aid students in their ability to understand topics regarding genetics.

- The description is then followed by the class diagram, depicting clearly what was described.

**Sample class Diagram from https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png:**

![Sample Diagram](https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png)

### Goals:

Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

- Objective 1:
- Objective 2:
- Objective n:

[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
