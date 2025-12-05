# InventoryManagement — C# Console Project

This is a simple C# console application demonstrating basic usage of **Generics** and the **List<T>** collection.  
The program simulates inventory operations such as adding, removing, checking existence, and retrieving a sub-range of items.

## ✨ Features
- Create and manage a `List<string>`
- Add single items (`Add`)
- Add multiple items at once (`AddRange`)
- Remove items
- Check if an element exists (`Contains`)
- Extract a portion of the list (`GetRange`)
- Iterate through the list using `foreach`

## 🧩 Code Example

```csharp
List<string> inventoryList = new List<string>();

inventoryList.Add("Printer");
inventoryList.Add("Laptop");
inventoryList.Add("Desk Chair");
inventoryList.Add("Monitor");
inventoryList.Add("Keyboard");
```

## ▶️ How to Run

1. Ensure you have **.NET SDK** installed  
2. Navigate to the project folder  
3. Run:

```
dotnet run
```

## 📁 Project Purpose
This project is educational and demonstrates how to work with **Generics** and the C# `List<T>` class.

---
Made by <V>.
