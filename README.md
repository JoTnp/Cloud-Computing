<style>
body{
    font-family: 'Segoe UI', sans-serif;
    background: linear-gradient(135deg,#0f172a,#1e293b);
    color:white;
    margin:0;
    padding:40px;
}

.container{
    max-width:1000px;
    margin:auto;
    background:rgba(255,255,255,0.05);
    backdrop-filter: blur(10px);
    padding:30px;
    border-radius:20px;
    box-shadow:0 0 20px rgba(0,0,0,0.3);
}

h1{
    text-align:center;
    color:#60a5fa;
    font-size:3rem;
    margin-bottom:10px;
}

.subtitle{
    text-align:center;
    color:#cbd5e1;
    margin-bottom:30px;
}

h2{
    color:#38bdf8;
    border-left:5px solid #38bdf8;
    padding-left:10px;
}

.card{
    background:rgba(255,255,255,0.08);
    padding:20px;
    margin:15px 0;
    border-radius:15px;
}

li{
    margin-bottom:10px;
    line-height:1.8;
}

a{
    color:#60a5fa;
    text-decoration:none;
}

a:hover{
    color:#a855f7;
}

.footer{
    text-align:center;
    margin-top:40px;
    color:#94a3b8;
}
</style>

<meta property="twitter:title" content="Function">

<h3> Definition </h3>
<ul>
  <li><strong>English (Source 1 - TechTarget) :</strong> "A function is a unit of code that is often defined by its role within a greater code structure. Specifically, a function contains a set of code that works on many kinds of inputs, like variables, expressions and produces a concrete result."</li>
  
  <li><strong>English (Source 2 - IBM) :</strong> "A function is a reusable block of code that performs a specific task. Functions help organize programs into manageable and modular sections."</li>
  
  <li><strong>Thai :</strong> Function คือ ชุดคำสั่งหรือกลุ่มของโค้ดที่ถูกสร้างขึ้นเพื่อทำงานเฉพาะอย่างใดอย่างหนึ่ง โดยสามารถเรียกใช้งานซ้ำได้หลายครั้ง ช่วยลดการเขียนโค้ดซ้ำ ทำให้โปรแกรมมีความเป็นระเบียบ อ่านง่าย และดูแลรักษาได้สะดวกมากขึ้น</li>
</ul>

---

<h3> Explanation </h3>
<ul>
  <li>Function เป็นแนวคิดพื้นฐานที่สำคัญในการเขียนโปรแกรม โดยทำหน้าที่รวบรวมชุดคำสั่งที่เกี่ยวข้องกับงานหนึ่ง ๆ ไว้ในส่วนเดียวกัน เมื่อโปรแกรมต้องการใช้งาน ก็สามารถเรียกใช้ Function นั้นได้ทันทีโดยไม่จำเป็นต้องเขียนโค้ดเดิมซ้ำหลายครั้ง</li>

  <li>ตัวอย่างเช่น หากโปรแกรมต้องคำนวณภาษีหรือคำนวณคะแนนรวมหลายครั้ง นักพัฒนาสามารถสร้าง Function สำหรับการคำนวณนั้นเพียงครั้งเดียว และเรียกใช้ซ้ำได้ทุกที่ภายในโปรแกรม</li>
    
  <li>องค์ประกอบของ Function <br>
&nbsp; 1. Function Name : ชื่อของฟังก์ชันที่ใช้สำหรับเรียกใช้งาน<br>
&nbsp; 2. Parameters : ข้อมูลที่ส่งเข้าไปให้ Function ใช้ในการประมวลผล<br>
&nbsp; 3. Return Value : ผลลัพธ์ที่ Function ส่งกลับ<br>
  </li>

  <li>ข้อดีของ Function <br>
&nbsp; • ลดการเขียนโค้ดซ้ำ (Code Reusability)<br>
&nbsp; • ทำให้โปรแกรมเป็นระเบียบมากขึ้น<br>
&nbsp; • ง่ายต่อการแก้ไขและบำรุงรักษา<br>
&nbsp; • ช่วยแบ่งงานออกเป็นส่วนย่อย ๆ<br>
&nbsp; • เพิ่มความเข้าใจในการอ่านโค้ด<br>
  </li>

  <li>"Function คือชุดคำสั่งที่ถูกรวมไว้เพื่อทำงานเฉพาะด้านหนึ่งของโปรแกรม สามารถรับข้อมูลเข้ามาประมวลผลและส่งผลลัพธ์กลับได้ ช่วยลดความซ้ำซ้อนของโค้ดและเพิ่มความเป็นระเบียบในการพัฒนาโปรแกรม" <strong>(ChatGPT)</strong></li>
  
  <li>"Function เป็นองค์ประกอบสำคัญของการเขียนโปรแกรมที่ช่วยแบ่งโปรแกรมออกเป็นส่วนย่อย ๆ แต่ละส่วนรับผิดชอบงานเฉพาะด้าน ทำให้โค้ดสามารถนำกลับมาใช้ซ้ำได้และช่วยให้การพัฒนาโปรแกรมมีประสิทธิภาพมากขึ้น"<strong>(Copilot)</strong></li>
</ul>

---

<h3> References </h3>
<ul>
  <li><a href="https://www.techtarget.com/">TechTarget - Function Definition</a></li>
  <li><a href="https://www.ibm.com/us-en">IBM - Programming Functions Overview</a></li>
</ul>
