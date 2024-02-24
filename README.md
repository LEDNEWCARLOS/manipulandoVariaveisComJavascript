# manipulandoVariaveisComJavascript
//obtendo a posição inicial do herói e o número total de passos apartir dos argumentos de linha de comando

const posicaoInicial = 
parseInt(process.argv[2]);
const totalPassos =
parseInt(process.argv[3]);

//Calculando a posição final do herói
const posicaoFinal = posicaoInicial + totalPassos;

//Exibindo a posição final do herói no console
console.log(" Aposição final do herói será:", posicaoFinal);

/*Execute o código fornecendo a posição inicial do herói e o número total de passos como argumentos de linhas de comando. Por exemplo "node classificador.js 2 3", isso calculará a posição final do herói no terminal do VsCode*/
