# ✾✽✣✤❀✿❃❁❋❊ HOMEWORK 1 ✾✽✣✤❀✿❃❁❋❊

##  ▒▒▒▒  งานแปล   ▒▒▒▒


# mkdir hw0001
	❆  สร้างโฟลเดอร์ใหม่ขึ้นมา โดยใช้ชื่อว่า hw0001 
	
# cd hw0001
	❆  เพื่อเข้าถึง dir hw0001 
	
# echo "# hw0001" >> README.md
	❆  เพิ่ม README ไฟล์  .md เข้าไปในไฟล์  hw0001 

# git init
	❆  สร้าง local repo ในโฟลเดอร์  hw0001

# git add README.md
	❆  เพิ่มไฟล์ชื่อ README.md เช้าไปในสถานะของ Staged
	
# git status
	❆  เป็นคำสั่งที่ใช้ตรวจสอบสถานะของ Source Code ในระบบ git
	
# git config --global user.email "karnkanok084@gmail.com"
	❆  กำหนดอีเมล์ของผู้ใช้ที่ใช้ใน github
	
# git config --global user.name "karnkanok"
	❆  กำหนดชื่อผู้ใช้ของเรา
	
# git commit -m "first commit"
	❆  การ commit คือการบันทึกความเปลี่ยนแปลงเข้าสู่ repo ของเรา เป็นการย้ายจาก staging state ไปยัง repository state นั่นเอง
	
# git remote add origin https://github.com/karnkanok/hw0001.git
	❆  เมื่อยังไม่มี remote repo เราก็จะเพิ่มเข้าไป โดยใช้ url ของโฟลเดอร์เรา
		
# git remote -v
	❆  แสดง remote Repository
	
# git push -u origin master
	❆  ให้เรากรอก username กับ password

