# Volvo Demo Deontic

## Getting Started

You can log on to the Deontic platform at <https://volvo.deontic.ai/>.
Please use the email address and password we have emailed to you. If you have not received a password, get in touch through <info@deontic.ai>.

<img width="1437" alt="Screenshot 2025-01-24 at 13 10 36" src="https://github.com/user-attachments/assets/a6d6fbf5-c05d-49f8-bb77-455b82655967" />

## Navigating the Interface

After logging on, you see a table with the requirements that are present in the database. These are dummy requirements that have been created by Deontic. 

For this demo, the requirement database is kept static. This means the requirements you enter, are not added to the database.

<img width="1418" alt="Screenshot 2025-01-24 at 13 11 10" src="https://github.com/user-attachments/assets/e397536a-92ce-4c7b-a130-212f770ea1d6" />

### Requirement Table
Every requirement in the table has an id, a title, a level, a creation date and a source document that they are linked to. You can browse through the table with the `Previous` and `Next` buttons in the bottom right corner. 

### Requirement Page
When you click the title of a requirement in the requirement table, you are taken to the requirement page, where you see its description and a list of similar requirements.

### Requirement Search
You can search the requirements using the search bar at the top of the requirement table. This search is semantic: it does not look for the literal terms that you enter, but for requirements with a similar meaning.

## Writing a New Requirement

To write a new requirement, click the `Create` button to the top right of the requirements table. This will take you to the ‘New requirement’ page.

### Requirement Fields
For every requirement you create, you need to provide the following pieces of information:

- Title: a title for the requirement.
- Requirement level: `Stakeholder`, `System`, or `Subsystem`. This choice will influence the feedback you get for a requirement: `stakeholder` requirements are more high-level, whereas `system` or `subsystem` requirements are more specific and must be verifiable.
- Description: the actual requirement

If you have filled in all three fields, click `Review`.

<img width="1147" alt="Screenshot 2025-01-24 at 13 12 55" src="https://github.com/user-attachments/assets/be33ab9e-12cc-4188-ba9c-78211c51a7f3" />


### Requirement Review
Our tool reviews several aspects of your requirement:

#### Deduplicate
Does your requirement potentially overlap with one or more requirements that are already in the database? You can check each of the potential duplicates by clicking them. The dialog that appears will not only show you the description of that requirement, but also explain why the tool thinks this requirement is a potential duplicate of yours.

<img width="1132" alt="Screenshot 2025-01-24 at 13 13 15" src="https://github.com/user-attachments/assets/6bb7b287-bb1c-4b33-825f-3ec284411e58" />


#### Clarify
Is your requirement clear and unambiguous? The feedback not only highlights possibly problematic words and phrases, but will also suggest an improvement.

<img width="1133" alt="Screenshot 2025-01-24 at 13 13 28" src="https://github.com/user-attachments/assets/0c280933-ff0b-4a6f-918d-8a167d64005c" />


#### Referral Detected
Does your requirement refer to an external source, such as another requirement or document, a piece of legislation or a standard? In some cases, it may be preferable to remove this referral to make the requirement more easily understandable and less ambiguous.

#### Split
Is your requirement atomic, or does it refer to multiple capabilities or functionalities? If so, it is advisable to split it up into multiple requirements. The tool will also suggest what these could look like.
Conflicting Requirements

<img width="1130" alt="Screenshot 2025-01-24 at 13 15 27" src="https://github.com/user-attachments/assets/904325f3-d722-4cc4-b74f-551dfc868264" />


### Resolve Conflict

<img width="1132" alt="Screenshot 2025-01-24 at 13 13 46" src="https://github.com/user-attachments/assets/ef8dc34f-8247-40c6-b800-f0213665ffbe" />

#### Similar Requirements
At the bottom of the page, you see a list of similar requirements. You can inspect each of these requirements by clicking them.

<img width="1046" alt="Screenshot 2025-01-24 at 13 14 13" src="https://github.com/user-attachments/assets/e0903c1d-599a-411d-a822-1650dae3c573" />

#### Improved Requirements
If our tool provides both `Clarify` and `Split` feedback, you will see a suggestion for `Improved requirements` at the top of the feedback, which combines the suggestions from the `Clarify` and `Split` fields.

<img width="1131" alt="Screenshot 2025-01-24 at 13 15 11" src="https://github.com/user-attachments/assets/4bb52de4-3d02-4705-b34a-8c37cb52dacb" />


### Submitting Feedback
When you’re happy with a requirement, click the `Create` button. Since the goal of this demo is to collect your feedback on its reviewing capabilities, you cannot click `Create` without first clicking `Review`.

When you click the `Create` button, a review form will appear that invites you to give feedback on the requirement review. First, this form will show you your original requirement and your final requirement. Next, it asks several questions:

1. Is the final requirement better than the original one?
2. Were the suggestions provided by the tool useful?
3. Does the final requirement have a correct syntactic form? For example, does it use the modal verb "shall" rather than "should", "must", "have to" or "need to"?
4. Does the final requirement conform to all criteria? It is clear and atomic, not a duplicate and not conflicting with existing requirements.
5. Finally, you can leave any other feedback you would like us to know.

Click ‘Submit’ to submit your feedback. Remember: your requirement will not be added to the Requirement Table.

<img width="778" alt="Screenshot 2025-01-24 at 13 17 46" src="https://github.com/user-attachments/assets/67ce8dbd-343c-4120-b190-410e5926be0b" />

### Logging out

You can log out by clicking your name at the bottom of the sidebar, and then clicking `Log out`.


