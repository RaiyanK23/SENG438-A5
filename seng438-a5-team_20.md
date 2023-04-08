**SENG 438- Software Testing, Reliability, and Quality**

**Lab. Report \#5 – Software Reliability Assessment**

| Group \#:       |   |
|-----------------|---|
| Student Names:  |   |
|                 |   |
|                 |   |
|                 |   |

# Introduction

The lab aimed to familiarize us with reliability assessment techniques such as C-SFRAT and the Reliability Demonstration Chart, as well as using Excel to analyze failure data. We will also have the opportunity to learn about reliability growth testing, which helps identify changes in a product's reliability over time. By examining failure data, we will determine how to prevent future failures. Through this lab, integration test data will be analyzed using both reliability growth testing and the Reliability Demonstration Chart, which allowed us to create models and plots for calculating MTTF, failure intensity, and software reliability. Also, each section of this lab serves the purpose of enhancing our understanding of reliability analysis and measurement, and we hope to learn how reliability certification can determine software quality. Ultimately, the lab will help us in recognizing when testing is necessary during software development.

# 

# Assessment Using Reliability Growth Testing 

# Assessment Using Reliability Demonstration Chart 

# 

# Comparison of Results

# Discussion on Similarity and Differences of the Two Techniques

Reliability Growth Analysis and Reliability Demonstration Chart are two system reliability techniques that can provide crucial insights about the Software Under Test (SUT) and its testing. Their similaririties include:

* Reliability Growth Analysis and Reliability Demonstration Chart are system reliability techniques.
* Both techniques rely on inter-failure times and MTTF.
* The same dataset of failures was used as input for both techniques.
* Both techniques were applied to test the same system.

Both Reliability Growth Analysis and Reliability Demonstration Chart interpret the data differently to develop distinct reliability plots for the system. Their differences include:

* Reliability Growth Analysis and Reliability Demonstration Chart interpret data differently to generate reliability plots for the system.
* Reliability Growth Analysis uses failure count and inter-failure times, while RDC only uses inter-failure times.
* Reliability Growth Analysis employs exponential and logarithmic Poisson models to estimate λ/λF ratios and track failure intensity trends.
* RDC uses Discrimination Ratio, Consumer Risk, and Developer Risk to evaluate the acceptability of the SUT.

# How the team work/effort was divided and managed

The team chose to collaborate on the lab project. We began first by installing the required tools. Together, we learned how to operate the tools and decided to use C-SFRAT because it was compatible with most laptops. However, Jacob and Kundai were not able to run the software because they both had Macbooks so Mohammed and Godwin worked on Part 1 using C-SFRAT and SRTAT while Kundai and Jacob worked on Part 2 using the RDC excel chart. Once all the necessary components were compiled and the graphs were created, the team collaborated to write the report and discuss their individual tools' functionality and results.

# Difficulties encountered, challenges overcome, and lessons learned

This lab was an interesting one, there were challenges encountered such as figuring out how to make the RDC Excel sheet take in more than 16 values, and modifying the data to fit the tools which took several hours. In addition, the SRTAT RDC only showed one failure data point which required assumptions to calculate the MTTFmin. Furthermore, the Reliability Growth Analysis had its own challenges such as CSFRAT being quite slow and the MTTF/MTBF calculation being complicated. It is important to note that while these tools can provide accurate results, they are only a simulation and the SUT needs to be thoroughly tested in reality. The tools cannot always be relied upon as the data is calculated and approximated within each tool, and a high learning curve and background knowledge is required for their functionality and result interpretation.

# Comments/feedback on the lab itself

The setup for the lab and a handful of the tools being used in the lab were found to be slightly problematic. In the sense that some people hand hinderances which slowed down the implementation process. On one hand, some of the issues that arised caused us to slow down and learn how the systems work on a more clear box level in order to solve them. However, it did have a small impact on the effeciency of the team getting the work done for the lab and learning what truly needed to be learned. 
