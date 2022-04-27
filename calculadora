using System;


namespace calculadora
{
    class calcular
    {
        static void Main()
        {
            int op, nv;   // variaveis do tipo inteiro
            float valor1, valor2, resultado = 0;  // variaveis do tipo real

            do {
                Console.WriteLine("DIGITE O VALOR 1:");
                valor1 = float.Parse(Console.ReadLine());
                Console.WriteLine("DIGITE O VALOR 2:");   // le do teclado dados do tipo real
                valor2 = float.Parse(Console.ReadLine());  // le do teclado dados do tipo real

                Console.Clear();   // limpa a tela no browser
                    Console.WriteLine("ESCOLHA UMA OPCAO");
                    Console.WriteLine(" 1 - PARA SOMAR");
                    Console.WriteLine(" 2 - PARA SUBTRAIR");
                    Console.WriteLine(" 3 - PARA MULTIPLICAR");
                    Console.WriteLine(" 4 - PARA DIVIDIR");
                    op = Convert.ToInt32(Console.ReadLine());     // le do teclado dados do tipo int

                    switch (op)
                    {
                        case 1:
                            resultado = valor1 + valor2;
                            break;
                        case 2:
                            resultado = valor1 - valor2;
                            break;
                        case 3:
                            resultado = valor1 * valor2;
                            break;
                        case 4:
                            resultado = valor1 / valor2;
                            break;
                        default:
                            Console.WriteLine("CODIGO INVALIDO");
                            break;

                    }

                Console.Clear();    // limpa a tela no browser

                Console.WriteLine("O RESULTADO FOI:" + resultado);
                Console.WriteLine('\n');
                Console.WriteLine("DIGITE 1 PARA CALCULAR NOVAMENTE:");
                Console.WriteLine("DIGITE 2 PARA FECHAR A CALCULADORA:");
                nv = Convert.ToInt32(Console.ReadLine());

                Console.Clear();    // limpa a tela no browser

            } while (nv == 1);  

            Console.ReadKey();    // da um break no browser, para nao fechar de uma vez

        }

    }

}
