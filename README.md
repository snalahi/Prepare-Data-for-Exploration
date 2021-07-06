# Prepare-Data-for-Exploration
Have you ever wondered why some online ads seem to make really accurate suggestions or how some websites remember your preferences? This is done using cookies, which are small files stored on computers that contain information about users. Cookies can help inform advertisers about your personal interests and habits based on your online surfing, without personally identifying you.

First-party data: This is data collected by an individual or group using their own resources.

Second-party data: which is data collected by a group directly from its audience and then sold. 

Third-party data or data collected from outside sources who did not collect it directly. 

A population refers to all possible data values in a certain data set. If you're analyzing data about car traffic in a city, your population would be all the cars in that area.

A sample is a part of a population that is representative of the population. You might collect a data sample about one spot in the city and analyze the traffic there, or you might pull a random sample from all existing data in the population. How you choose your sample will depend on your project.

Historical data, which is data that already exists.

Discrete data: This is data that's counted and has a limited number of values. Discrete data isn't limited to dollar amounts. Examples of other discrete data are stars and points. When partial measurements (half-stars or quarter-points) aren't allowed, the data is discrete. If you don't accept anything other than full stars or points, the data is considered discrete.

Continuous Data: Data that is measured and can have almost any numeric value. Continuous data can be measured using a timer, and its value can be shown as a decimal with several places.

Nominal data is a type of qualitative data that is categorized without a set order. In other words, this data doesn't have a sequence.

Ordinal data, on the other hand, is a type of qualitative data with a set order or scale.

Internal data, which is data that lives within a company's own systems.

External data: Data that lives and is generated outside of an organization.

Structured data is data that is organized in a certain format, such as rows and columns. Spreadsheets and relational databases are two examples of software
that can store data in a structured way.

Unstructured data: Data that is not organized in any easily identifiable manner. Audio and video files are examples of unstructured data because there's no clear way to identify or organize their content.

Data Model: Data model is used for organizing data elements and how they relate to one another. Structured data works nicely within a data model. Data models help to keep data consistent and provide a map of how data is organized. This makes it easier for analysts and other stakeholders to make sense of their data and use it for business purposes.

What are data elements? => They're pieces of information, such as people's names, account numbers, and addresses. 

#### Data Modelling: https://www.coursera.org/learn/data-preparation/supplement/vtp7L/data-modeling-levels-and-techniques

A data type is a specific kind of data attribute that tells what kind of value the data is. In other words, a data type tells you what kind of data you're working with.

A data type in a spreadsheet can be one of three things: a number, a text or string, or a Boolean.

A text data type, or a string data type, which is a sequence of characters and punctuation that contains textual information.

A Boolean data type is a data type with only two possible values: true or false.

You can call the rows "records" and the columns "fields."

Two mostly used data formats are: Wide Data and Long Data.

Wide Data => Every data subject has a single row with multiple columns to hold the values of various attributes of the subject.

Long data => is data in which each row is one time point per subject, so each subject will have data in multiple rows. The long data format keeps everything nice and compact. 

If you're wondering which format you should use, the simple answer is, "it depends." Sometimes you'll have to transform wide data into a long data format, or
other times vice versa.

#### Data Transformation: https://www.coursera.org/learn/data-preparation/supplement/EOCT4/transforming-data

Data transformation enables data analysts to change the structure of data.

The Boolean operator OR expands the number of results when used in a keyword search.

Data transformation can change the structure of the data. An example of this is taking data stored in one format and converting it to another.

Bias is a preference in favor of or against a person, group of people, or thing.
```
Skew => - A bias towards one particular group or subject (noun).
          exp: "the paper had a working-class skew"
        - The state of not being symmetrical (Statistics).
        - Make biased or distorted in a way that is regarded as inaccurate, unfair,
          or misleading (verb).
          exp: "the curriculum is skewed towards the practical subjects"
        - Cause (a distribution) to be asymmetrical (Statistics).
          exp: "the distributions were skewed to the right"
```

Data bias is a type of error that systematically skews results in a certain direction.

```
Implication => The conclusion that can be drawn from something although it is not
               explicitly stated.
```

Unbiased Sampling is a sample that is representative of the population being measured.

There are four types of data bias: sampling bias, observer bias, interpretation bias, and confirmation bias.

Sampling Bias => A sample that is not representative of the population as a whole.

Observer Bias => which is sometimes referred to as experimenter bias or research bias. Basically, it's the tendency for different people to observe things differently. 

Interpretation Bias => The tendency to always interpret ambiguous situations in a positive, or negative way.

Confirmation Bias => is the tendency to search for, or interpret information in a way that confirms preexisting beliefs. Someone might be so eager to confirm a gut feeling, that they only notice things that support it, ignoring all other signals. This happens all the time in everyday life.

```
A "citation" is the way you tell your readers that certain material in your work came
from another source. It also gives your readers the information necessary to find that
source again, including:

-- information about the author
-- the title of the work
-- the name and location of the company that published your copy of the source
-- the date your copy was published
-- the page numbers of the material you
```

Vetted public datasets, academic papers, and governmental agency data are usually good data sources.

Third-party data about an older version of the product is inappropriate because it is not original or current.

Ethics refers to well-founded standards of right and wrong that prescribe what humans ought to do, usually in terms of rights, obligations, benefits to society, fairness or specific virtues. 

Data ethics refers to well- founded standards of right and wrong that dictate how data is collected, shared, and used.

#### Six most important aspects or concerns of data ethics: ownership, transaction transparency, consent, currency, privacy, and openness.

Openness of Data (or Open Data) => Free access, usage, and sharing of data. Interoperability is key to open data's success. Companies have to cooperate and
work together to make data useful. Databases must be accessible with common formats and terminology. 

Personally identifiable information, or PII, is information that can be used by itself or with other data to track down a person's identity.

Data anonymization is the process of protecting people's private or sensitive data by eliminating that kind of information (PII). Typically, data anonymization involves blanking, hashing, or masking personal information, often by using fixed-length codes to represent data columns, or hiding data with altered values. 

Healthcare and financial data are two of the most sensitive types of data. These industries rely a lot on data anonymization techniques. After all, the stakes are very high. That’s why data in these two industries usually goes through de-identification, which is a process used to wipe data clean of all personally identifying information.

#### Transaction transparency states that all data-processing activities and algorithms should be completely explainable and understood by the individual who provides their data.

#### Consent is the aspect of data ethics that presumes an individual’s right to know how and why their personal data will be used before agreeing to provide it.

In general, the usefulness of data decreases as time passes. The best data sources are current and relevant.

Data privacy refers to preserving a data subject’s information and activity for all data transactions.

#### Database is a collection of data stored in a computer system. 

#### A relational database is a database that contains a series of tables that can be connected to show relationships. Basically, they allow data analysts to organize and link data based on what the data has in common. 

#### A primary key is an identifier that references a column in which each value is unique.

#### A foreign key is a field within a table that's a primary key in another table. 

#### Normalized database is a database in which only related data is stored at each table.         

#### A redundancy occurs when the same piece of data is stored in two or more separate places. 

#### A schema is a way of describing the way something is organized. You can think about data schemas like blueprints of how the database is constructed.

#### Metadata: Data about data. Keep in mind that metadata is not the data itself. Instead, it's data about the data. In data analytics, metadata helps data analysts interpret the contents of the data within a database. That's why metadata is so important when working with databases. 

There are three common types of metadata: descriptive, structural, and administrative.
- Descriptive metadata is metadata that describes a piece of data and can be used to identify it at a later point in time.
- Structural metadata, which is metadata that indicates how a piece of data is organized and whether it's part of one or more than one data collection.
- Administrative metadata is metadata that indicates the technical source of a digital asset.   

A metadata repository is a database specifically created to store metadata. Metadata repositories can be stored in a physical location, or they can be virtual, like data that exists in the cloud. A data analyst uses a metadata repository to access metadata quickly, maintain the metadata’s structure, and store metadata in a database. 

Data governance is a process to ensure the formal management of a company’s data assets. This gives an organization better control of their data and
helps a company manage issues related to data security and privacy, integrity, usability, and internal and external data flows. 

When we introduce `sort range` in spreadsheet the data will be sorted on the first mentioned column, then depending upon that it will be sorted on the second column and so on.

Column names should be written in lowercase and for names with multiple words, in snake case, which separates each word with an underscore to make it more readable. Column names should never contain spaces.


































