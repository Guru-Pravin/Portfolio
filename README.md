## PRD for Taxfixer

**Purpose**

  **Tax Fixer** is a two-page web application that allows users to upload investment and insurance documents (PDF or JPEG). The system validates and Extracts document data using Optical Character Recognition (OCR) and displays a summary along with smart recommendations Users can also provide their email or phone number to receive future updates.

**Objective**
-   Provide users with an easy way to upload tax-related documents.
    
-   Automatically extract, validate, and summarize document information.
    
- Generate and show  Summary from the given documents  
- Offer personalized tax-saving smart recommendations.
    
-   Enable users to opt-in for future updates(optional).

**FlowChart**

![tax fixer_flow](https://github.com/user-attachments/assets/e4a819d2-9352-47c9-b17d-bd296047dc3d)




## **Functional Requirements**

### **Page 1: Document Upload and Validation**

 **File Upload:**
    
   -   Users can upload Multiple investment and insurance documents in PDF or JPEG format.
        
   -   System shows the acknowledgement for the document attachment(List of documents attached)
        
**Document Validation**
 -   Ensure all documents belong to the  **current financial year**.
    
 -   Validate document types (Payslip,investment or insurance).
    
 -   Verify that all documents belong to the  **same user**  (based on extracted user name or ID).

 **Error Handling:**
    
 -   Display clear error messages for invalid documents Such as
	   -  "This document does not belong to the current financial year".
	   - "All the Documents doesn't belong to the same person"
	   - "Invalid Document format"
        
  -   Allow users to re-upload corrected documents.

**User Contact Information:**

 -   Allow users to provide their email or phone number to receive future updates.
    
 -   Validate email/phone number format.

**Page 2**
**Document Summary**
   

 - Display a summary of the uploaded documents, including:
       
     -   Total investment amount.
           
   	 -   Total insurance premium paid.
           
   	  -   Breakdown by document type.

**Smart Recommendations**
-   Provide Personalized actionable recommendations based on the uploaded documents, such as:
    
    -   Tax-saving tips.
        
    -   Suggested investments or insurance plans.
        
    -   Estimated tax liability or refund.

 **User Story and Acceptance Criteria**



**File Upload**


|User Story|Acceptance Criteria  |
|--|--|
| As A User,I want to upload my investment and insurance documents so that the system can process them. |-   Users should be able to upload PDF or JPEG files.  |
||A size limit of singe document should be mentioned.
||Maximum number of documents can be mentioned


**File Validation**
| User Story | Acceptance Criteria |
|--|--|
| As a User,I want to see clear error messages if my documents are invalid. |   Documents not belonging to the current financial year should be neglected and notify the User.|
||   Invalid document types should be rejected.
|| Documents belonging to different users should be identified and show error message to user


**Real-Time Summary**

|User Story|Acceptance Criteria  |
|--|--|
| As a user,  I want to see a summary of my uploaded documents,|System should display summary of the given input data including total investment amount, total insurance premium, and breakdown by document type.

**Smart Tax-Saving Recommendations**

|User Story|Acceptance Criteria  |
|--|--|
| As a user,I want to receive personalized tax-saving suggestions,So that I can reduce my tax liability | Suggestions should be given based on given inputs |
||Should Include at least two actionable recommendations with estimated tax savings.
|**Providing Contact Information:**
|As a User,I want to provide my email or phone number so that I can receive future updates and Recommendations|Users should be able to provide their email or phone number.
||Invalid email/phone number formats should be notified with an error message


**Enhancements**
 - This application will provide a simple tool(like an Extension)for guided real-time tax filing,









