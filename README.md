**Cake Business Invoice Generator**
A simple Python tool for generating monthly Excel invoices with auto-filled dates and invoice numbers, created for a small business when I was 16. This was my first-ever project, built with openpyxl and PyQt5.

_Features_

Generates invoices for the specified number of days.

Automatically fills in dates and increments invoice numbers.

Simple and easy-to-use interface with PyQt5.

Ready-to-fill Excel files for daily sales.

Does not adjust for months with fewer than 31 days (dates may go beyond the current month, e.g., 31, 32, etc.).

**Technologies Used**
Python

openpyxl (for Excel file generation)

PyQt5 (for graphical user interface)

Installation

Clone the repository:

git clone https://github.com/adamabida/project0.git

Install the required Python packages:

pip install -r requirements.txt


_How It Works_

Enter the starting date, the number of invoices you want, and the starting invoice number.

The program generates invoices for the number of days requested, with dates and invoice numbers filled in.  

Open the generated Excel files and fill in the sales data.

The program does not handle date overflow beyond the current month (e.g., it will show 31, 32, etc., if the number of invoices exceeds the days in the current month).

The paths of the file to be copied and the generated files location should be accessed from the code itself

_PS:
I know this program isn’t perfect, and I didn’t fix the issue with dates exceeding the number of days in the current month because I was the only one using it. I also didn’t want to change it now, as it still holds value to me. Even though the program is really simple, it took me quite a while back then to get used to coding, and I’m proud of it._
