Cafe Management System

A standalone desktop application for efficient cafe operations, built with Java and Java Swing. This system simplifies user management, menu administration, order tracking, and PDF bill generation, tailored for small to medium-sized cafes.

🚀 Features





User Management: Add new staff users and set up a default admin with secure, role-based access.



Menu Administration: Admins can add, update, or delete food items and categories for dynamic menu management.



Order Tracking: Real-time tracking of customer orders with detailed order views.



PDF Bill Generation: Generate professional PDF bills for completed orders using Apache PDFBox.



Point-of-Sale (POS): User-friendly interface for quick order processing and payments.



Data Storage: SQLite with JDBC for reliable, local data persistence in a standalone setup.

🛠️ Tech Stack





Backend: Java 8+ (Core Java for business logic and PDF generation)



Frontend: Java Swing (JFrames, JPanels, JTables for GUI)



Database: SQLite (via JDBC for lightweight, embedded storage)



PDF Library: Apache PDFBox (for bill creation and export)



Build Tool: Maven (for dependency management)

📋 Prerequisites





Java Development Kit (JDK) 8 or higher



Maven (for dependency resolution)



IDE: IntelliJ IDEA, Eclipse, or NetBeans recommended



Apache PDFBox library (included via Maven dependencies)

🏃‍♂️ Installation





Clone the repository:

git clone https://github.com/yourusername/cafe-management-system.git



Open the project in your IDE.



Resolve Maven dependencies (Apache PDFBox, SQLite JDBC, etc.).



Run CafeManagementSystem.java as the main class.



On first launch, configure the default admin account to manage users, menu, and orders.

📖 Usage





Admin Features: Log in as admin to manage food items, categories, and staff accounts.



Staff Features: Staff can process orders, view order details, and generate PDF bills.



PDF Bills: Bills are saved as PDFs in the output directory upon order completion.
