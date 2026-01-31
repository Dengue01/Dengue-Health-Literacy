<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<title>แบบประเมินความรอบรู้</title>
<style>
body{
  font-family: Tahoma, sans-serif;
  background:#f2f6ff;
  padding:20px;
}
.container{
  max-width:900px;
  margin:auto;
  background:#fff;
  padding:25px;
  border-radius:10px;
  box-shadow:0 0 10px rgba(0,0,0,0.1);
}
h2{
  text-align:center;
  color:#1e40af;
}
h3{
  color:#2563eb;
  margin-top:25px;
}
.question{
  margin-bottom:12px;
}
.result{
  margin-top:25px;
  padding:15px;
  background:#eef2ff;
  border-radius:8px;
  font-size:18px;
  font-weight:bold;
}
button{
  padding:10px 25px;
  font-size:16px;
  background:#2563eb;
  color:white;
  border:none;
  border-radius:6px;
  cursor:pointer;
}
button:hover{
  background:#1e40af;
}
.scale{
  font-size:14px;
  color:#555;
  margin-bottom:15px;
}
</style>
</head>

<body>
<div class="container">

<h2>แบบประเมินระดับความรอบรู้</h2>

<div class="scale">
ระดับคะแนน:  
1 = น้อยที่สุด | 2 = น้อย | 3 = ปานกลาง | 4 = มาก | 5 = มากที่สุด
</div>

<form id="quiz">

<!-- ด้านที่ 1 -->
<h3>ด้านที่ 1 การเข้าถึงข้อมูลสุขภาพ (Access)</h3>
<div class="question">1. ท่านสามารถค้นหาข้อมูลเกี่ยวกับโรคไข้เลือดออกได้ด้วยตนเอง<br>
<input type="radio" name="q1" value="1">1
<input type="radio" name="q1" value="2">2
<input type="radio" name="q1" value="3">3
<input type="radio" name="q1" value="4">4
<input type="radio" name="q1" value="5">5
</div>
<div class="question">2. ท่านทราบแหล่งข้อมูลที่เชื่อถือได้เกี่ยวกับโรคไข้เลือดออก</div>
<div class="question">3. ท่านได้รับข้อมูลข่าวสารเกี่ยวกับการระบาดของโรคไข้เลือดออกอย่างต่อเนื่อง</div>
<div class="question">4. ท่านสามารถขอคำแนะนำเรื่องไข้เลือดออกจากบุคลากรสาธารณสุขได้</div>
<div class="question">5. ท่านติดตามสื่อหรือประกาศเตือนเกี่ยวกับโรคไข้เลือดออก</div>

<!-- ด้านที่ 2 -->
<h3>ด้านที่ 2 ความเข้าใจข้อมูลสุขภาพ (Understand)</h3>
<div class="question">6. ท่านเข้าใจสาเหตุการเกิดโรคไข้เลือดออก</div>
<div class="question">7. ท่านเข้าใจวิธีการติดต่อของโรคไข้เลือดออก</div>
<div class="question">8. ท่านเข้าใจอาการสำคัญของโรคไข้เลือดออก</div>
<div class="question">9. ท่านเข้าใจอาการอันตรายที่ต้องรีบไปพบแพทย์</div>
<div class="question">10. ท่านเข้าใจวิธีการป้องกันโรคไข้เลือดออกที่ถูกต้อง</div>

<!-- ด้านที่ 3 -->
<h3>ด้านที่ 3 การประเมินข้อมูลสุขภาพ (Appraise)</h3>
<div class="question">11. ท่านสามารถแยกแยะข้อมูลจริงและข่าวลือเกี่ยวกับโรคไข้เลือดออกได้</div>
<div class="question">12. ท่านพิจารณาความน่าเชื่อถือของแหล่งข้อมูลก่อนเชื่อหรือปฏิบัติตาม</div>
<div class="question">13. ท่านไม่หลงเชื่อวิธีรักษาไข้เลือดออกที่ไม่มีหลักฐานทางการแพทย์</div>
<div class="question">14. ท่านเปรียบเทียบข้อมูลจากหลายแหล่งก่อนตัดสินใจ</div>
<div class="question">15. ท่านสามารถตัดสินใจได้ว่าข้อมูลใดควรนำไปใช้</div>

<!-- ด้านที่ 4 -->
<h3>ด้านที่ 4 การตัดสินใจและการนำไปใช้ (Apply)</h3>
<div class="question">16. ท่านกำจัดแหล่งเพาะพันธุ์ยุงลายรอบบ้านเป็นประจำ</div>
<div class="question">17. ท่านใช้วิธีป้องกันยุงลาย เช่น มุ้ง ยากันยุง หรือมุ้งลวด</div>
<div class="question">18. ท่านปรับพฤติกรรมในครัวเรือนเพื่อลดความเสี่ยงต่อไข้เลือดออก</div>
<div class="question">19. เมื่อสงสัยว่าเป็นไข้เลือดออก ท่านไปพบแพทย์ทันที</div>
<div class="question">20. ท่านหลีกเลี่ยงการซื้อยารับประทานเองเมื่อมีไข้สูง</div>

<!-- ด้านที่ 5 -->
<h3>ด้านที่ 5 การสื่อสารด้านสุขภาพ (Communicate)</h3>
<div class="question">21. ท่านสามารถอธิบายสาเหตุและการป้องกันไข้เลือดออกให้ผู้อื่นเข้าใจได้</div>
<div class="question">22. ท่านแนะนำคนในครอบครัวให้ช่วยกันป้องกันโรคไข้เลือดออก</div>
<div class="question">23. ท่านกล้าสอบถามเจ้าหน้าที่สาธารณสุขเมื่อมีข้อสงสัย</div>
<div class="question">24. ท่านแลกเปลี่ยนข้อมูลการป้องกันไข้เลือดออกกับเพื่อนบ้านหรือชุมชน</div>
<div class="question">25. ท่านแจ้งเตือนผู้อื่นเมื่อพบแหล่งเพาะพันธุ์ยุงลาย</div>

<!-- ด้านที่ 6 -->
<h3>ด้านที่ 6 การจัดการตนเองและการมีส่วนร่วม (Self-management & Participation)</h3>
<div class="question">26. ท่านดูแลตนเองและครอบครัวให้ปฏิบัติตามมาตรการป้องกันอย่างสม่ำเสมอ</div>
<div class="question">27. ท่านมีส่วนร่วมในการกำจัดลูกน้ำยุงลายในบ้านหรือชุมชน</div>
<div class="question">28. ท่านปฏิบัติตามคำแนะนำของเจ้าหน้าที่สาธารณสุขอย่างต่อเนื่อง</div>
<div class="question">29. ท่านเข้าร่วมกิจกรรมรณรงค์ป้องกันโรคไข้เลือดออกในชุมชน</div>
<div class="question">30. ท่านเห็นความสำคัญของการป้องกันโรคไข้เลือดออกในระยะยาว</div>

<button type="button" onclick="calculate()">ประเมินผล</button>
</form>

<div id="result" class="result"></div>

</div>

<script>
function calculate(){
  let total = 0;
  for(let i=1;i<=30;i++){
    let q = document.querySelector(`input[name="q${i}"]:checked`);
    if(!q){
      alert("กรุณาตอบให้ครบทุกข้อ");
      return;
    }
    total += parseInt(q.value);
  }

  let level="";
  if(total<=30) level="น้อยที่สุด";
  else if(total<=60) level="น้อย";
  else if(total<=90) level="ปานกลาง";
  else if(total<=120) level="มาก";
  else level="มากที่สุด";

  document.getElementById("result").innerHTML =
    `คะแนนรวม: ${total}<br>ระดับความรอบรู้: ${level}`;
}
</script>

</body>
</html>
