
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

Parent class: This class represents the organism participating in breeding. 
Attributes:

-parent_genotype(Genotype): The Genotype object of the parent

-name (str): identifier for which parent it is

Method:

+get_gamete(): Provides possible allele combination for gametes using Mendel's Laws of Segregation and Independent Assortment.

Allele class: This class represents each individual variant of a gene

Attributes:

-letter (str): The literal letter symbol for a certain allele e.g. "t" or "T"
  
-is_dominant (bool): Attribute determining whether the allele is dominant or recessive.
  
Methods:

+__str__(): returns the string symbol

Genes class: This class represents a single possible trait

Attributes:

-name (str): name of a specific trait such as flower color
  
-alleles (list): list of possible Allele objects for a specific gene
  
Methods:

+dominant_allele(): Returns dominant alleles
  
+recessive_allele(): Returns recessive alleles

Genotype class: This class represents a combination of alleles

Attributes:

-child_genotype (str): A specific combination of alleles such as "Tt"
  
Methods:

+get_genotype(): Provides the probability of getting an offspring with the exact child_genotype among all possibilities.

+get_phenotype(): Provides the actual observable traits such as "Purple flower"

A Gene contains one to many Alleles, a Genotype uses Genes, a Parent posseses a Genotype. 

The expected output of the program is to compute and print the results of the get_genotype() and get_phenotype() methods, simulating inheritance.


- Include the description as well of your target demographics as the user of your application.

The target demographic and user of this application are high school students around Grade 9 or younger that can benefit from being able to play around with different parent genotypes to see how it affects the phenotypic and genotypic ratio of the offspring. This can aid students in their ability to understand topics regarding genetics.

- The description is then followed by the class diagram, depicting clearly what was described.

**(Class diagram is also in untitled.pdf)**
<img width="802" height="750" alt="Screenshot 2026-11-12 200949" src="https://github.com/user-attachments/assets/dd4c6e2c-91f1-4e71-9d14-25f825821189" />

**Sample class Diagram from https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png:**

![Sample Diagram](https://static.visual-paradigm.com/web/images/tutorials/class-diagram-tutorial/01-class-diagram-example.png)

### Goals:

Describe the long term outcomes of your project followed by a couple of objectives to meet the goals stated in this paragraph

- Long-Term: Help students quickly visualize and calculate Mendelian inheritance ratios, saving time spent on traditional methods of determining phenotypic and genotypic ratios.
- Objective 1: Create a software tool with the use of OOP that accurately produces genotypic and phenotypic ratios.
- Objective 2: Provide precise results and predictions for the probability of acquiring a specific genotypic or phenotypic combination using Mendel's Laws.


[Click here for Rubrics and Sample projects](https://docs.google.com/document/d/1xKd1CqK6DcNWS2_oJPBNtY5n3I3Hqiw8FY3W295Iqfk/edit?usp=sharing)
