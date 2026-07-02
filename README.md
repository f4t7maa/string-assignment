[string.py](https://github.com/user-attachments/files/29610650/string.py)
# string-assignment"""Q2 — E-Commerce Product Code Analyzer
code = "MOB-APPLE-IPHONE15PRO-256GB-BLACK"
# print product category
print(code [0:3])
# print company name
print(code [4:9])
# print model name
print(code [11:21])
# print storage size
print(code [23:27])
# print product color
print(code [28:33])
# print first character of company name
print(code[4])
# print last character of model name
print(code[20])"""


"""Q3 — Online Banking SMS Processor
#transferred amount only
rupees = "PKR"
money = "25000"
amount = rupees + " " + money
print(amount)
#print account number only
account = "Account"
no = "45892"
accno = account + " " + no 
print(accno)
#print transaction status word only
status = "succesfully"
done = "transfered"
do = status + " " + done
print(do)
#print first 25 characters
text = "PKR 25000 has been successfully transferred to account 45892 "
print(text [0:25])
#• print last 15 characters
print(text [-15:-1])
#count how many times letter "a" appears
print(text.count("a"))"""





"""#Q4 — University Student Record Formatter
text = "BSCS|2026|045|Muhammad Ali Khan"
print("department ===>",text [0:4])
print("year ===>",text [5:9])
print("roll no ===>",text [10:13])
print("name ===>", text [14:31] )
print("first name ===>", text [14:26])
print("initialls ===>", text [14])"""



"""#Q5 — Website URL Processing System
text = "https://www.amazonshoppingstore.com"
print(text [8:]) 
print(text [12:])
print(text [12:31])
print(text [32:len(text)])
print(text.endswith(".com"))
print(text [8:31])"""



"""#Q6 — Secure Password Formatter
text = "AB39876" 
print("Hiden pass ===>",len(text) * "*" )
print("first character ===>",text[0])
print("last character ===>",text[-1])
print("pass len ===>",len(text))
print("middle character ===>",text[3:4])
print("password endswith ===>" ,text.endswith("6"))"""



"""Q7 — File Management System
text = "python_final_project_documentation_2026.pdf "
jo = text.replace("_" , " " )
print(jo)
print(text[:39] )
print(text[-5:-1])
print(text.endswith(".pdf "))
print(text[0:20])
print(text[-10:-1])"""



"""#Q8 — Social Media Username Generator
text = "fatima_ibrahim_pubg_21 " 
print(text[:14])
print(text[15:19])
print(text[20:22])
print(text[0:8])
print(text[-7:-1])
print(text.capitalize() [:14])
"""


"""text = "hello sir i have completed my python assignment successfully "
print(text.capitalize())
print(text.replace("python","javascript"))
print(text.find("assignment"))
print(text.count("s"))
print(text[0:18])
print(text[-20:-1])
print(text[17:26])
"""


"""#Q10 — Online Course Information System
text = "Python Programming Complete Bootcamp 2026 "
print(text[0:17])
print(text[-4:-1])
print(text[0])
print(text[0:15])
print(text[-13:-1])
print(text.count("o"))
print(text.endswith(" 2026 "))"""



#Q1 — Professional Email Management System
text = "muhammad.ahmed2026@softwarehouse.com"
print()
