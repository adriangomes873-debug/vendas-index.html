<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rose Mimo - Beleza, Mimos e Variedades</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif}
body{background:#fff8fb}
header{background:linear-gradient(135deg,#c2185b,#ff4fa3);color:#fff;padding:28px;text-align:center}
header h1{font-size:30px;letter-spacing:1px}
.container{max-width:1100px;margin:auto;padding:15px}
h2{color:#c2185b;margin:22px 0 10px;border-left:5px solid #ff4fa3;padding-left:10px;font-size:18px}
.products{display:grid;grid-template-columns:repeat(auto-fill,minmax(165px,1fr));gap:12px}
.card{background:#fff;border-radius:18px;padding:10px;box-shadow:0 3px 12px rgba(0,0,0,.06);text-align:center;display:flex;flex-direction:column}
.card .img{height:160px;background:#fff;border-radius:12px;overflow:hidden;display:flex;align-items:center;justify-content:center}
.card .img img{width:100%;height:100%;object-fit:contain}
.card h3{font-size:12.5px;margin:7px 0 2px;font-weight:700;line-height:14px;height:28px}
.desc{font-size:10.5px;color:#666;line-height:12px;height:30px;overflow:hidden}
.price{color:#ff4fa3;font-weight:800;font-size:18px;margin:6px 0}
.btn{background:#ff4fa3;color:#fff;border:none;padding:9px;border-radius:20px;width:100%;cursor:pointer;font-weight:700;font-size:12px;margin-top:auto}
.btn:hover{background:#c2185b}
#cartIcon{position:fixed;bottom:20px;right:18px;background:#c2185b;color:#fff;padding:14px 22px;border-radius:30px;cursor:pointer;font-weight:700;z-index:100;box-shadow:0 5px 20px rgba(0,0,0,.3)}
#cart{position:fixed;bottom:80px;right:18px;background:#fff;border-radius:18px;box-shadow:0 8px 30px rgba(0,0,0,.25);padding:16px;width:315px;max-height:75vh;overflow:auto;display:none;z-index:101}
.cart-item{display:flex;justify-content:space-between;font-size:12px;padding:4px 0;border-bottom:1px dashed #ffd0e2}
#cartTotal{font-weight:800;color:#ff4fa3;text-align:right;margin-top:8px;font-size:15px}
#btnFinalizar{background:#25D366;color:#fff;padding:12px;width:100%;border:none;border-radius:25px;margin-top:10px;font-weight:800;cursor:pointer}
footer{background:#222;color:#ddd;text-align:center;padding:22px;margin-top:30px;font-size:12px}
footer a{color:#ff8abf;text-decoration:none}
</style>
</head>
<body>
<header>
<h1>👑 ROSE MIMO 🌹</h1>
<p>Beleza, Mimos e Variedades | Itaitinga-CE</p>
<p>WhatsApp: (85) 98700-5202 | @mimosdarosevariedades</p>
</header>

<div class="container">
<h2>💄 Maquiagem</h2>
<div class="products">
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380427349/Blush-duo.jpg"></div><h3>Blush Compacto Duo Ruby Rose</h3><div class="desc">Alta pigmentação, 2 cores lindas</div><div class="price">R$ 10,00</div><button class="btn" onclick="add('Blush Duo',10)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380377046/Blush%20compactado.jpg"></div><h3>Blush Compacto Playback</h3><div class="desc">Cor intensa que dura o dia todo</div><div class="price">R$ 14,00</div><button class="btn" onclick="add('Blush Playback',14)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380515615/candylip.jpg"></div><h3>Candy Lip Oil PhalleBeauty</h3><div class="desc">Brilho + hidratação, boca macia</div><div class="price">R$ 10,00</div><button class="btn" onclick="add('Candy Lip Oil',10)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380711997/Lip%20fruit.jpg"></div><h3>Lip Gloss Lip Fruit Melancia</h3><div class="desc">JummyJu 15g com chaveirinho</div><div class="price">R$ 10,00</div><button class="btn" onclick="add('Lip Gloss Fruit',10)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380737219/delineador.jpg"></div><h3>Delineador Ultra Black Vivai</h3><div class="desc">Preto intenso, não borra</div><div class="price">R$ 12,00</div><button class="btn" onclick="add('Delineador',12)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380853563/Lapis-pink21.jpg"></div><h3>Lápis Olho e Lábio Pink21</h3><div class="desc">2 em 1, macio e pigmentado</div><div class="price">R$ 5,00</div><button class="btn" onclick="add('Lápis Pink21',5)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380873943/P%C3%83%C2%B3%20compacto.jpg"></div><h3>Pó Compacto Popstar</h3><div class="desc">Fancy Face - pele sequinha</div><div class="price">R$ 10,00</div><button class="btn" onclick="add('Pó Compacto',10)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380888554/P%C3%83%C2%B3%20de%20banana.jpg"></div><h3>Pó de Banana Swiss Beauty</h3><div class="desc">Sela a make, não estoura no flash</div><div class="price">R$ 10,00</div><button class="btn" onclick="add('Pó de Banana',10)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380724811/esponja.jpg"></div><h3>Esponja Chanfrada</h3><div class="desc">Kit 3 cores, acabamento profissional</div><div class="price">R$ 5,00</div><button class="btn" onclick="add('Esponja',5)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381065318/Mascara-cilios.jpg"></div><h3>Máscara de Cílios</h3><div class="desc">Volume e alongamento</div><div class="price">R$ 10,00</div><button class="btn" onclick="add('Máscara Cílios',10)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380442611/brilho-labial.jpg"></div><h3>Brilho Labial</h3><div class="desc">Boca luminosa o dia todo</div><div class="price">R$ 10,00</div><button class="btn" onclick="add('Brilho Labial',10)">Adicionar</button></div>
</div>
<div class="card">
    <div class="img">
        <img src="https://uploads.onecompiler.io/454bxpyrs/1790380669893/Candy%20lip%20oil.jpg" alt="Lip Oil Change Color Hudamoji">
    </div>

    <h3>Lip Oil Change Color Hudamoji</h3>

    <div class="desc">
        Lip oil hidratante com efeito change color
    </div>

    <div class="price">
        R$ 10,00
    </div>

    <button class="btn" onclick="add('Lip Oil Change Color Hudamoji', 10)">
        Adicionar
    </button>
</div>

<h2>🧴 Cuidados e Higiene</h2>
<div class="products">
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381126635/Sabonete-abacaxi.jpg"></div><h3>Sabonete Líquido Brisa Abacaxi 1L</h3><div class="desc">Suavidade e proteção 1 litro</div><div class="price">R$ 10,00</div><button class="btn" onclick="add('Sabonete Abacaxi 1L',10)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381317788/Escova%20de%20cabelo.jpg"></div><h3>Escova de Cabelo</h3><div class="desc">Desembaraça sem quebrar</div><div class="price">R$ 10,00</div><button class="btn" onclick="add('Escova Cabelo',10)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381330397/Escova%20massageadora.jpg"></div><h3>Escova Massageadora</h3><div class="desc">Massageia e ativa circulação</div><div class="price">R$ 8,00</div><button class="btn" onclick="add('Escova Massageadora',8)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790380245557/Agua-micelar.jpg"></div><h3>Água Micelar</h3><div class="desc">Limpa e hidrata sem arder - Rose</div><div class="price">R$ 12,00</div><button class="btn" onclick="add('Água Micelar',12)">Adicionar</button></div>
<div class="card"><div class="img"><img src= "https://uploads.onecompiler.io/454bxpyrs/1790381138795/d.jpg" </div><h3>Esfoliante Rosto e Corpo</h3><div class="desc">Pele lisinha e renovada</div><div class="price">R$ 20,00</div><button class="btn" onclick="add('Esfoliante',20)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381157498/sintimo.jpg"</div><h3>Sabonete Íntimo</h3><div class="desc">Cuidado delicado diário</div><div class="price">R$ 12,00</div><button class="btn" onclick="add('Sabonete Íntimo',12)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381253749/touca.jpg"></div><h3>Touca de Cetim</h3><div class="desc">Dupla face, sem frizz</div><div class="price">R$ 5,00</div><button class="btn" onclick="add('Touca Cetim',5)">Adicionar</button></div>
</div>

<h2>💖 Acessórios e Variedades</h2>
<div class="products">
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381435300/Xuxinha.jpg"></div><h3>Xuxinha Cetim</h3><div class="desc">Não marca nem quebra</div><div class="price">R$ 3,00</div><button class="btn" onclick="add('Xuxinha',3)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381832502/Len%C3%83%C2%A7o%20umedecido%20P.jpg"</div><h3>Lenço Fácil P Yasmim</h3><div class="desc">Aloe Vera e Laranja</div><div class="price">R$ 5,00</div><button class="btn" onclick="add('Lenço P',5)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381738367/Len%C3%83%C2%A7o%20umedecido%20G.jpg"></div><h3>Lenço Fácil G 30un Hudamoji</h3><div class="desc">Mais folhas, mais economia</div><div class="price">R$ 8,00</div><button class="btn" onclick="add('Lenço G',8)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381650824/p.jpg"></div><h3>Piranha Brilhosa Metalizada</h3><div class="desc">Brilho máximo, 6 cores</div><div class="price">R$ 6,00</div><button class="btn" onclick="add('Piranha Brilhosa',6)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381483704/p-florp.jpg"></div><h3>Piranha Flor Plástico P</h3><div class="desc">Flor plumeria delicada</div><div class="price">R$ 5,00</div><button class="btn" onclick="add('Piranha Flor',5)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381501674/Piranha%20pl%C3%83%C2%A1stico%20P%20.jpg"></div><h3>Piranha Plástico P Trançada</h3><div class="desc">Mini mas prende firme</div><div class="price">R$ 4,00</div><button class="btn" onclick="add('Piranha P',4)">Adicionar</button></div>
<div class="card"><div class="img"><img src="https://uploads.onecompiler.io/454bxpyrs/1790381468139/Piranha%20brilhosa%20G.jpg"</div><h3> Piranha Plástico Brilhante G</h3><div class="desc">Tamanho grande, segura muito</div><div class="price">R$ 6,00</div><button class="btn" onclick="add('Piranha G',6)">Adicionar</button></div>
</div>
</div>

<div id="cartIcon" onclick="toggle()">🛒 Carrinho (<span id="qtd">0</span>)</div>
<div id="cart"><div id="itens"></div><div id="cartTotal">Total: R$0,00</div><button id="btnFinalizar" onclick="zap()">Finalizar no WhatsApp</button></div>

<footer>
<p><strong>ROSE MIMO - Beleza, Mimos e Variedades</strong></p>
<p>📍 Itaitinga-CE | 📲 (85) 98700-5202</p>
<p>📸 @mimosdarosevariedades</p>
</footer>

<script>
let carrinho=[];
function add(nome,preco){carrinho.push({nome,preco}); upd(); document.getElementById('cart').style.display='block';}
function upd(){let h="";let t=0; carrinho.forEach(p=>{t+=p.preco; h+=`<div class="cart-item"><span>${p.nome}</span><span>R$${p.preco}</span></div>`}); document.getElementById('itens').innerHTML=h||"<p style='font-size:12px;color:#888'>Vazio</p>"; document.getElementById('cartTotal').innerText="Total: R$"+t+",00"; document.getElementById('qtd').innerText=carrinho.length;}
function toggle(){let c=document.getElementById('cart'); c.style.display=c.style.display=='block'?'none':'block';}
function zap(){if(!carrinho.length){alert('Carrinho vazio');return;}let t=0;let m="Olá Rose Mimo! 🌹 Vim pelo site e quero:%0A"; carrinho.forEach(p=>{t+=p.preco; m+=`- ${p.nome} R$${p.preco}%0A`}); m+=`%0A*Total: R$${t},00*%0A%0AComo combinamos entrega?`; window.open("https://wa.me/5585987005202?text="+m,"_blank");}
</script>
</body>
</html>
