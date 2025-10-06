# 📝  ToDoListApplication (iOS)

A simple and elegant **ToDo List app** built using **SwiftUI** and **MVVM architecture**.  
This app demonstrates the use of **CRUD operations (Create, Read, Update, Delete)** to manage tasks efficiently — all with beautiful animations and a clean design.


---

## 🚀 Features

- ✅ **Add new tasks** with a title and details  
- 🗒️ **View all tasks** in an organized list  
- 🖊️ **Edit existing tasks** seamlessly  
- ❌ **Delete tasks** with a swipe gesture  
- 💾 **Persistent local storage** (using `UserDefaults` / `CoreData`)  
- 🎨 **Modern UI** built fully in **SwiftUI**  
- 🧠 **MVVM architecture** for clean and scalable code  
- 💫 **Animations** for buttons and view transitions  

---

## 🏗️ Architecture Overview

The app follows the **MVVM (Model–View–ViewModel)** pattern for clear separation of concerns.

### Example Flow
1. **ViewModel** manages the list of tasks and handles saving/deleting.  
2. **View** observes ViewModel via `@StateObject` or `@ObservedObject`.  
3. **Model** represents a single ToDo item (`id`, `title`, `isCompleted`).  

---

## 🧩 Project Structure


---

## ⚙️ CRUD Implementation

| Operation | Description | SwiftUI Integration |
|------------|--------------|---------------------|
| **Create** | Add new item | `AddView` with `@EnvironmentObject` |
| **Read**   | Display list | `List` in `ContentView` |
| **Update** | Edit existing | `onTapGesture` / `EditView` |
| **Delete** | Remove task | `onDelete(perform:)` in `List` |

---

## 📱 Screenshots (Optional)
> *(Add screenshots or GIFs here)*  
Example:  
| Home Screen | Add Task | No Items View |
|--------------|-----------|----------------|
| ![](screenshots/home.png) | ![](screenshots/add.png) | ![](screenshots/noitems.png) |

---

## 🧠 Technologies Used

- **Swift 5+**
- **SwiftUI**
- **MVVM Architecture**
- **Combine Framework**
- **CoreData / UserDefaults**
- **Xcode 16+**

---

## 🛠️ How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ToDoListApplication.git

---

Would you like me to tailor the README for your **exact implementation** (for example, if you’re using **UserDefaults** or **CoreData** for storage and if you have screenshots)?  
I can insert that detail automatically to make it match your actual code.

