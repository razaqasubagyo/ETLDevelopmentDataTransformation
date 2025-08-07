<h1>ETL Development: Data Transformation</h1>


<h2>Overview</h2>
Implemented various transformation techniques in Talend to normalize, restructure and integrate data from multiple sources, enabling efficient downstream processing and analytics.
<br />


<h2>Key Highlights</h2>

- **Normalization:** Used the `tNormalize` component to normalize data by removing duplicate rows, handling null values, and trimming empty strings through advanced settings configuration.

- **Joining Tables:** Used the `tJoin` and `tMap` components to combine data from multiple tables and applied filter transformations by configuring expressions filters within the component. In a separate job, utilized multiple `tMap` components to transform one table independently before joining to optimize performance.

- **Extracting Data:** Extracted various data formats using Talend components, including `tExtractJSONFields` (via JSONPath queries) for JSON files, `tExtractXMLField` (via XPath queries) for XML files, and `tExtractPositionalFields` for delimited files. Also used `tExtractRegexFields` to parse delimited files with regular expressions. 


<h2>Skills </h2>

Talend Open Studio, Data Transformation, Normalization & Denormalization, Data Integration.

<h2>Documentation:</h2>

<p align="center">
Normalization & Denormalization - Job Designer Workflow <br/>
<img src="https://github.com/user-attachments/assets/b15aa4b2-4507-48ed-b63a-2d78b6628581" height="80%" width="80%" alt="Schema Handling"/>
<br />
<br />
Join Tables with tJoin - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/75935558-f1a7-465a-a409-198c02bd201f" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Join & Filter Tables with tMap - Job Designer Workflow <br/>
<img src="https://github.com/user-attachments/assets/0a4d744f-e8d6-494b-89d0-d0332e0099c4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Join & Filter Tables with tMap - Mapping Configuration  <br/>
<img src="https://github.com/user-attachments/assets/7ee25ced-3451-48c8-baa4-bc3ba59a180d" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Join Tables with Multiple tMap - Job Designer Workflow  <br/>
<img src="https://github.com/user-attachments/assets/8f41372b-b74c-488e-9cf3-eed62b8fa0d7" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Join Tables with Multiple tMap - Second tMap Mapping Configuration  <br/>
<img src="https://github.com/user-attachments/assets/8f869a9e-bc56-4210-b34e-8bc6e1c64aee" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Extracting Data - Job Designer Workflow (A)  <br/>
<img src="https://github.com/user-attachments/assets/cd757b62-d1cc-495f-81e7-1441a26dde1e" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Extracting Data - Job Designer Workflow (B)  <br/>
<img src="https://github.com/user-attachments/assets/eca2bf51-06ca-48e7-81d3-2737ba8e1190" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
