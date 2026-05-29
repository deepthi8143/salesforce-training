# 📘 Salesforce Day 9 Notes

# ⚡ Component Communication

Components communicate to:
- Share data
- Trigger actions
- Update UI dynamically
- Improve modular architecture

---

# 👨‍👩‍👧 Parent-Child Communication

## Parent Component
Controls and passes data.

## Child Component
Receives data and displays information.

Communication happens using:
- Properties
- Events
- Methods

---

# 🔄 Event-Driven UI

Events help components react automatically when actions occur.

### Examples
- Button click
- Form submission
- Notification update
- Attendance change

---

# 🏫 Dashboard Architecture

# 🎓 Student Dashboard
Components:
- Header Component
- Student Info Component
- Attendance Component
- Notification Component

---

# 👨‍🏫 Faculty Dashboard
Components:
- Faculty Profile
- Course Management
- Student List
- Notifications

---

# 🛠️ Admin Dashboard
Components:
- Reports Component
- Student Management
- Faculty Management
- System Notifications

---

# 🔗 Component Communication Example

## Student Dashboard Flow

Header Component →
Student Info Component →
Attendance Component →
Notification Component

All components communicate to update data dynamically.

---

# 🌐 Data Flow Thinking

## Student Registration Process

### UI
Student enters registration details.

↓

### Validation
Validation Rules check email and required fields.

↓

### Flow
Flow sends confirmation email.

↓

### Apex
Apex handles advanced business logic.

↓

### Database
Records stored in Salesforce database.

↓

### Notification
Admin and faculty receive notifications.

---

# 🆚 Aura vs LWC

| Aura | LWC |
|---|---|
| Older framework | Modern framework |
| Less performance | Faster performance |
| Complex architecture | Simpler architecture |
| More custom framework | Uses web standards |

---

# 🌐 Why Salesforce Moved Toward LWC

Salesforce moved toward LWC because:
- Better performance
- Modern JavaScript standards
- Faster UI rendering
- Improved scalability
- Better developer experience

---

# 🧠 Reflection

Enterprise systems use modular architecture because:
- Components become reusable
- Maintenance becomes easier
- Development becomes scalable
- Teams can work independently
- Systems become organized and efficient
