# Compracerta
string nomeproduto;
double valor,total, parcelamento;
int quantidade;

Console.WriteLine("Digite o nome do produto");
nomeproduto = Console.ReadLine();
Console.WriteLine("Digite o valor do produto");
valor = double.Parse(Console.ReadLine());
Console.WriteLine("Digite a Quantidade do produto");
quantidade = int.Parse(Console.ReadLine());




total = quantidade * valor;
parcelamento = total / 3;




if (valor > 300)
{
    Console.WriteLine("Você é um bom cliente");

}

else
{
    Console.WriteLine("Você é um cliente mediano");
}
Console.WriteLine("O Valor total da sua compra é de R$ " + total);
Console.WriteLine("No parcelamento de 3 vezes fica a R$ " + parcelamento);


//Rômulo Henrique Barros Pestana//
