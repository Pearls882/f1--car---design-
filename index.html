# f1--car---design-
<!DOCTYPE html>
<html lang="th">
<head>
  <meta charset="UTF-8">
  <title>เกมออกแบบรถ F1</title>
  <script src="https://cdn.jsdelivr.net/npm/html2canvas@1.4.1/dist/html2canvas.min.js"></script>
  <style>
    body {
      font-family: sans-serif;
      text-align: center;
      background: #f4f4f4;
      padding: 20px;
    }

    .car-preview {
      width: 300px;
      height: 150px;
      margin: 20px auto;
      border-radius: 20px;
      background-color: red;
      position: relative;
      background-size: cover;
      background-repeat: no-repeat;
      box-shadow: 0 0 10px rgba(0,0,0,0.5);
    }

    .form-section {
      margin-top: 20px;
    }

    select, button {
      padding: 10px;
      margin: 10px;
      font-size: 16px;
    }

    #score {
      font-size: 20px;
      margin-top: 10px;
    }
  </style>
</head>
<body>
  <h1>🎮 เกมออกแบบรถ F1</h1>

  <div class="form-section">
    <label>เลือกสีรถ:
      <select id="colorSelect">
        <option value="red">แดง</option>
        <option value="blue">น้ำเงิน</option>
        <option value="black">ดำ</option>
      </select>
    </label>
    <br>
    <label>เลือกลวดลาย:
      <select id="patternSelect">
        <option value="none">ไม่มี</option>
        <option value="stripes">ลายทาง</option>
        <option value="dots">ลายจุด</option>
        <option value="waves">ลายคลื่น</option>
      </select>
    </label>
    <br>
    <button onclick="updateCar()">แสดงรถ!</button>
    <button onclick="saveImage()">💾 บันทึกรูปรถ</button>
    <button onclick="shareCar()">📤 แชร์รถ</button>
  </div>

  <div id="carPreview" class="car-preview"></div>
  <div id="score">คะแนนความสวยงาม: -</div>

  <script>
    function updateCar() {
      const color = document.getElementById("colorSelect").value;
      const pattern = document.getElementById("patternSelect").value;
      const car = document.getElementById("carPreview");

      // สี
      car.style.backgroundColor = color;

      // ลวดลาย
      switch (pattern) {
        case "stripes":
          car.style.backgroundImage = "repeating-linear-gradient(45deg, rgba(255,255,255,0.2) 0, rgba(255,255,255,0.2) 10px, transparent 10px, transparent 20px)";
          break;
        case "dots":
          car.style.backgroundImage = "radial-gradient(white 5%, transparent 6%)";
          car.style.backgroundSize = "20px 20px";
          break;
        case "waves":
          car.style.backgroundImage = "repeating-linear-gradient(90deg, rgba(255,255,255,0.3) 0px, rgba(255,255,255,0.3) 5px, transparent 5px, transparent 10px)";
          break;
        default:
          car.style.backgroundImage = "none";
      }

      // คำนวณคะแนน
      const score = calculateScore(color,
