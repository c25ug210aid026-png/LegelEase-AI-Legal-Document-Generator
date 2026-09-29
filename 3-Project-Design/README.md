# 3. Project Design Phase

### UI/UX Design:
- Homepage: Clean, professional with 3 document cards
- Form Page: Step-by-step input fields
- Preview Page: Generated document with edit option
- Download Page: PDF download button

### Wireframe:
[Home] -> [Select Doc Type] -> [Fill Form] -> [AI Generation] -> [Preview] -> [Download PDF]

### Database Design:
- Users table: id, name, email, password
- Documents table: id, user_id, type, content, created_at

### AI Prompt Design:
"You are a legal expert. Create a professional [DOCUMENT_TYPE] with following details: [USER_DETAILS]. Use formal legal language."
