<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=Edge">
  <meta name="viewport" content="width=device-width, initial-scale=1">

  <title>Winnie the Pooh</title>
  
  <!-- HTML -->
  

  <!-- Custom Styles -->
  <link rel="stylesheet" href="style.css">
  <style>
    h1 {
      font-size: 40px;
      font-family: helvetica;
      text-align: center;
      position: relative;
      bottom: -200px;
    }
  
    .winnie-the-pooh {
      position: relative;
      bottom: -700px;
      right: -300px;
    }
    
    .kepala-atas {
      background-color: #ECC441;
      position: relative;
      width: 200px;
      height: 95px;
      clip-path: polygon(20% 0%, 80% 0%, 100% 100%, 0% 100%);
      border-radius: 40%;
    }
    .kepala-bawah {
      background-color: #ECC441;
      width: 206px;
      height: 130px;
      border-radius: 50%;
      position: relative;
      top: -55px;
      left: -3px;
    }
    .telinga-kanan {
      background-color: #ECC441;
      width: 52px;
      height: 52px;
      border-radius: 50%;
      position: relative;
      top: -255px;
      right: -137px;
    }
    .telinga-kiri {
      background-color: #ECC441;
      width: 52px;
      height: 52px;
      border-radius: 50%;
      position: relative;
      top: -307px;
      right: -13px;
    }
    .hidung {
      background-color: black;
      width: 25px;
      height: 20px;
      border-radius: 10px 10px 25px 25px;
      position: relative;
      top: -228px;
      right: -89px;
    }
    .mata-kanan {
      background-color: black;
      width: 16px;
      height: 20px;
      border-radius: 50%;
      position: relative;
      top: -285px;
      right: -135px;
    }
    .mata-kiri {
      background-color: black;
      width: 16px;
      height: 20px;
      border-radius: 50%;
      position: relative;
      top: -305px;
      right: -51px;
    }
    .alis-kanan {
      width: 18px;
      height: 6px;
      border: 3px solid black;
      border-top-left-radius: 87px;
      border-top-right-radius: 87px;
      border-bottom: none;
      position: relative;
      top: -354px;
      right: -135px;
    }
    .alis-kiri {
      width: 18px;
      height: 6px;
      border: 3px solid black;
      border-top-left-radius: 87px;
      border-top-right-radius: 87px;
      border-bottom: none;
      position: relative;
      top: -362px;
      right: -45px;
    }
    .badan {
      background-color: #ECC441;
      width: 229px;
      height: 268px;
      border-radius: 44%;
      position: relative;
      top: -279px;
      left: -13px;
      z-index: -1;
    }
    .baju-depan {
      background-color: darkred;
      width: 274px;
      height: 135px;
      border-bottom-left-radius: 40%;
      border-bottom-right-radius: 40%;
      clip-path: polygon(20% 0%, 80% 0%, 100% 100%, 0% 100%);
      position: relative;
      top: -520px;
      left: -36px;
      z-index: -1;
    }
    .baju-kiri {
      background-color: darkred;
      width: 65px;
      height: 87px;
      position: relative;
      top: -660px;
      left: -19px;
      z-index: -1;
      transform: rotate(50deg);
      
    }
    .baju-kanan {
      background-color: darkred;
      width: 65px;
      height: 87px;
      position: relative;
      top: -753px;
      right: -155px;
      z-index: -1;
      transform: rotate(-50deg);
       
    }
    .tangan-kiri {
      background-color: #ECC441;
      width: 67px;
      height: 83px;
      border-radius: 42%;
      position: relative;
      top: -789px;
      left: -57px;
      z-index: -2;
      transform: rotate(50deg);
    }
    .tangan-kanan {
      background-color: #ECC441;
      width: 67px;
      height: 83px;
      border-radius: 42%;
      position: relative;
      top: -878px;
      right: -194px;
      z-index: -2;
      transform: rotate(-50deg);
    }
    .kaki-kanan {
      background-color: #ECC441;
      width: 68px;
      height: 100px;
      border-radius: 46%;
      position: relative;
      top: -825px;
      right: -130px;
    }
    .kaki-kiri {
      background-color: #ECC441;
      width: 68px;
      height: 100px;
      border-radius: 46%;
      position: relative;
      top: -924px;
      left: 0px;
    }
    .shadow {
      background-color: dimgrey;
      opacity: 25%;
      width: 275px;
      height: 70px;
      border-radius: 50%;
      position: relative;
      top: -987px;
      left: -15%;
      z-index: -2;
    }
    .balon {
      position: relative;
      left: -8%;
      top: 115%;
    }

    .balon {
      width: 150px;
      height: 163px;
      background: radial-gradient(circle, #fff 20%, maroon 80%);
      border-radius: 50%;
      position: absolute;
      animation: float 4s ease-in-out infinite;
      box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
    }

    .balon::after {
      content: '';
      position: absolute;
      bottom: -50px;
      left: 50%;
      width: 3px;
      height: 100px;
      background: #333;
      transform: translateX(-50%);
    }

    .red {
      left: 0;
      animation-delay: 0s;
      
    }

    .blue {
      left: 220px;
      animation-delay: 2s;
    }

    @keyframes float {
      0% {
        transform: translateY(0);
      }
      50% {
        transform: translateY(-150px);
      }
      100% {
        transform: translateY(0);
      }
    }
    
  </style>
</head>

<body>
  <h1>☁️🌈Balon buat kamu☁️🌈</h1>
  <div class="winnie-the-pooh">
    <div class="kepala-atas"></div>
    <div class="kepala-bawah"></div>
    <div class="telinga-kanan"></div>
    <div class="telinga-kiri"></div>
    <div class="hidung"></div>
    <div class="mata-kanan"></div>
    <div class="mata-kiri"></div>
    <div class="alis-kanan"></div>
    <div class="alis-kiri"></div>
    <div class="badan"></div>
    <div class="baju-depan"></div>
    <div class="baju-kiri"></div>
    <div class="baju-kanan"></div>
    <div class="tangan-kiri"></div>
    <div class="tangan-kanan"></div>
    <div class="kaki-kanan"></div>
    <div class="kaki-kiri"></div>
    <div class="shadow"></div>
  </div>
  <div class="balon">
    <div class="balon red"></div>
    <div class="balon blue"></div>
  </div>
  
  <script src="main.js"></script>
</body>
</html>
