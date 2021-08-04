

<html lang="in">

<head>

				<title>Chat Web</title>

				<style>
          body{
				background:gainsboro;
}


.judul{
				background-color:#191919;
				position:fixed;
				top:0;
				left:0;
				right:0;
				
				
}



.what{
				color:white;
				font-family:Cursive;
				opacity:1;
				text-align:center;
				
}

.input{
				position:fixed;
				bottom:35px;
				left:0;
                                right:0;
				
				
				
}


.pesan{
				width:70%;
				border:none;
				text-decoration:none;
				background:#191919;
				color:white;
				padding:5px;
				margin-left:7%;
				border-radius:5px; font-size:7px;
				
}

.kirim{
				width:20%;
				border:none;
				text-decoration:none;
				background:#191919;
				padding:5px;
				text-align:center;
				color:white;
				border-radius:5px;
}

.robot{
				text-align:center;
				
				font-size:20px;
}

.text{
				
			
				text-align:center;
				font-size:6.5px;
			  
				color:#191919;
				
}


.isi{
				margin-top:50%;
}

.textt{
				background:white;
				width:70%;
				height:100px;
				margin:auto;
				display:block;
				box-shadow: 0px 10px 10px grey;
				border-radius:5px;
				padding:5px; font-size:6.5px;
}

.bawah{
				position:fixed;
				bottom:0;
				left:0;
				right:0;
				background:#191919; padding:3px;
				
}

.prytna{
				text-align:center;
				color:white;
				font-size:11px;
}

          </style>

</head>

<body>

				<div class="judul">

								

								<h3 class="what">Gues Mate</h3>

				</div>

				

				

			<div class="isi">

							<div class="textt">

											

				<h3 class="text" id="text"><em>Masukan bulan lahir kamu dengan huruf kecil</em></h3>

				

				</div>

				

				</div>

				

				

				

				<div class="input">

								<input type="text" class="pesan" placeholder="Ketik pesan" id="pesan">

								<button class="kirim" id="kirim" onclick="kirim()">Kirim</button>

				</div>

				

				<div class="bawah">

								<p class="prytna">Prytna Web Deisgn, Copyright &copy; 2019</p>

				</div>

			

<script>

function kirim() {

  var text;

  var pesan = document.getElementById("pesan").value;

  switch(pesan) {

    case "januari":

      text = "memiliki kepribadian yang serba cepat.Ia tidak memiliki toleransi untuk seorang yang melemahkan langkahnya menuju seuatu.Pasangan yang cocok dengannya adalah seorang yang juga berkemauan keras, penuh ambisi dan bergerak cepat.";

    break;

    case "februari":

    text = "memiliki sifat yang sangat keras kepala tetapi berhati lembut, mereka cocok dengan sosok seseorang yang berhati lembut dan tidak kasar";

    break;

    case "maret":

    text = "seorang yang sangat peduli, berwawasan luas dan sangat memuja pasangan Kamu memerlukan pasangan yang memiliki sifat serupa untuk mendapatkan timba balik";

    break;

    case "april":

    text = "sifat dari bulan april mempunyai sifat mandiri dan berusaha dengan giat untuk mencapai sesuatu apalago dengan kekasih tercinta nya";

    break;

    case "mei":

    text = "memiliki sifat yang rajin dan cepat dalam sega la urusan, mudah untuk memecahkan masalah yang rumit";

    break;

    case "juni":

    text = "di dalam diri bulan juni itu kreatif dan mudah bergaul dengan orang orang di sekitarnya dan memiliki percaya diri yang tinggi";

    break;

    case "juli":

    text = "Dia tidak akan pernah gagal untuk menjadi romantis. Selain itu, dia juga merupakan sosok orang yang rumit, karena pesona alami yang memang telah dimilikinya.";

    break;

    case "agustus":

    text = "memiliki sifat yang mandiri dan keras kepala tetapi memiliki hati yang lemah lembut, dia memiliki sifat yang jujur";

    break;

    case "september":

    text = "Sosok yang lahir di bulan September tahu bagaimana cara memberi kejutan bagi pasangannya Dia tahu bagaimana caranya melepaskan berbagai hal kecil dan menikmati waktu bersama pasanganya";

    break;

    case "oktober":

  text="Dia adalah tipe seseorang yang cerdas, tepat, dan bisa berkomunikasi dengan baik. Dia bisa membuat pasangan merasa istimewa hanya menggunakan kata- kata saja.";

    break;

    case "november":

    text = "Sosok yang lahir di bulan November adalah tipe suami yang sangat kreatif dan ramah, tipe yang berbahaya, karena pasangan tidak akan pernah bisa marah.";

    break;

    case "desember":

    text = "Dia mungkin adalah sosok yang paling santai yang pernah ditemui oleh seseorang. Ia adalah sosok yang bisa menyeimbangkan keadaan, melihat berbaga hal dengan perspektif yang berbeda, membuat pasangan nyaman melalui saat yang paling sulit sekalipun.";

    break;

    default:

    text = "Harap masukan bulan lahir anda dengan huruf kecil dan benar";

  }

  document.getElementById("text").innerHTML = text;

}

</script>

</body>

</html>

