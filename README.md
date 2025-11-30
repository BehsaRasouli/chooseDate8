# ChooseDate App

A simple Windows Forms application that allows the user to pick a date using a **DateTimePicker** and display it in a label by clicking a button.

## ✨ Features
- Select any date using the built-in DateTimePicker control  
- Display the chosen date in `yyyy/mm/dd` format  
- Clean and minimal UI  
- Beginner-friendly .NET WinForms example

## 🖼️ How It Works
1. Choose a date from the DateTimePicker  
2. Click the **Show Date** button  
3. The selected date appears in the label  

## 📌 Code Snippet
```csharp
private void button1_Click(object sender, EventArgs e)
{
    label1.Text = "Selected Date is: " + dateTimePicker1.Value.ToString("yyyy/mm/dd");
}
![chooseDate](https://github.com/user-attachments/assets/655906e8-6bae-4703-a89f-9637e360d2fd)
