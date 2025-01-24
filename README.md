# Volvo Demo Deontic

## Getting Started

You can log on to the Deontic platform at [https://volvo.deontic.ai/](https://volvo.deontic.ai/).
Please use the email address and password we have emailed to you. If you have not received a password, get in touch through `info@deontic.ai`.

## Navigating the Interface

After logging on, you see a table with the requirements that are present in the database. These are dummy requirements that have been created by Deontic. 

For this demo, the requirement database is kept static. This means the requirements you enter, are not added to the database.

### Requirement Table
Every requirement in the table has an id, a title, a level, a creation date and a source document that they are linked to. You can browse through the table with the ‘Previous’ and ‘Next’ buttons in the bottom right corner. 

### Requirement Page
When you click the title of a requirement in the requirement table, you are taken to the requirement page, where you see its description and a list of similar requirements.

### Requirement Search
You can search the requirements using the search bar at the top of the requirement table. This search is semantic: it does not look for the literal terms that you enter, but for requirements with a similar meaning.

## Writing a New Requirement

To write a new requirement, click the ‘Create’ button to the top right of the requirements table. This will take you to the ‘New requirement’ page.

### Requirement Fields
For every requirement you create, you need to provide the following pieces of information:

- Title: a title for the requirement.
- Requirement level: ‘Stakeholder’, ‘System’, or ‘Subsystem’. This choice will influence the feedback you get for a requirement: ‘stakeholder’ requirements are more high-level, whereas ‘system’ or ‘subsystem’ requirements are more specific and need to be verifiable.
- Description: the actual requirement

If you have filled in all three fields, click ‘Review’.

### Requirement Review
Our tool reviews several aspects of your requirement:

#### Deduplicate
Does your requirement potentially overlap with one or more requirements that are already in the database? You can check each of the potential duplicates by clicking them. The dialog that appears will not only show you the description of that requirement, but also explain why the tool thinks this requirement is a potential duplicate of yours.

#### Clarify
Is your requirement clear and unambiguous? The feedback not only highlights possibly problematic words and phrases, but will also suggest an improvement.

#### Referral Detected
Does your requirement refer to an external source, such as another requirement or document, a piece of legislation or a standard? In some cases, it may be preferable to remove this referral to make the requirement more easily understandable and less ambiguous.

#### Split
Is your requirement atomic, or does it refer to multiple capabilities or functionalities? If so, it is advisable to split it up into multiple requirements. The tool will also suggest what these could look like.
Conflicting Requirements

#### Similar Requirements
At the bottom of the page, you see a list of similar requirements. You can inspect each of these requirements by clicking them.

#### Improved Requirements
If our tool provides both ‘Clarify’ and ‘Split’ feedback, you will see a suggestion for ‘Improved requirements’ at the top of the feedback, which combines the suggestions from the Clarify and Split fields.

### Submitting Feedback
When you’re happy with a requirement, click the ‘Create’ button. Since the goal of this demo is to collect your feedback on its reviewing capabilities, you cannot click ‘Create’ without first clicking ‘Review’.

When you click the ‘Create’ button, a review form will appear that invites you to give feedback on the requirement review. First, this form will show you your original requirement and your final requirement. Next, it asks several questions:

1. Is the final requirement better than the original one?
2. Were the suggestions provided by the tool useful?
3. Does the final requirement have a correct syntactic form? For example, does it use the modal verb ‘shall’ rather than ‘should’, ‘must’, ‘have to’ or ‘need to’?
4. Does the final requirement conform to all criteria? It is clear and atomic, not a duplicate and not conflicting with existing requirements.
5. Finally, you can leave any other feedback you would like us to know.

Click ‘Submit’ to submit your feedback. Remember: your requirement will not be added to the Requirement Table.




