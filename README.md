
*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
display: flex;
  flex-direction: column;
  min-height: 100vh;
  background-color: #f5f2f2;
}

.cabecalho {
  background-color: #c96530;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 15px 25px;
}

.cabecalho-link {
  color: #fff;
  text-decoration: none;
}

h1 {
  color: #fff;
  font-size: 24px;
}

.cartao {
width: 260px;
height: 200px;
}

.cartao-imagem {
width: 100%;
}

main {
  flex: 1;
}

footer {
  background-color: #c96530;
  padding: 15px 25px;
  color: #fff;
}
