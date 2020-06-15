package FirstTextRPGame;
import java.util.Scanner;


public class game{

public static void main(String[] args){
    Scanner in = new Scanner(System.in);
    //hp dos personagens (0 = proprio, 1 = ovidio, 2 = evandro, 3 = Marcio)
    int[] hp = {100,100,100,1000};
    //nome dos inimigos
    String[] nomeInimigo = {"Ovidio", "Evandro", "Eliney", "Marcio"};
    //dano dos inimigos (5 = Ovidio, 10 = Evandro, 30 = Marcio)
    int[] dano = {5, 10, 500};
    String nome;
    System.out.println("Para começar o jogo, Digite seu nome: ");
    //gravar o nome do seu personagem em uma variavel
    nome = in.nextLine();
    //variaveis de escolha
    int escolha;
    int opcaoCerta = 1;
    //variavel para continuar o texto
    int cont;
    //introdução como historia
    System.out.print("=============================================================================================================");
    System.out.println("======================================================================");
    System.out.println("O Ano é 2077, " + nome + " decidiu se aventurar pela cidade de Sorocaba que a muito tempo está abandonada, ");
        System.out.println("Digite 1 para continuar");
            cont = in.nextInt();
            if(cont == 1){}            
    System.out.println("até encontrar uma antiga faculdade chamada FACENS, e então você decide entrar.");
        System.out.println("Digite 1 para continuar");
            cont = in.nextInt();
            if(cont == 1){}                              
    System.out.println("era um lugar totalmente obscuro, e " + nome + " começou a escutar barulhos na sala de informatica, foi dar uma olhada");
        System.out.println("Digite 1 para continuar");
            cont = in.nextInt();
            if(cont == 1){} 
    System.out.println("onde havia historias de que um tal de Ovidio se habitava por lá, logo ao entrar, uma pessoa te segura e te ameaça com uma faca, ");
        System.out.println("Digite 1 para continuar");
            cont = in.nextInt();
            if(cont == 1){} 
    System.out.print("=============================================================================================================");
    System.out.println("======================================================================");
    System.out.println("Você escapou e precisa imediatamente de uma arma para se defender.");
        System.out.println("Digite 1 para continuar");
            cont = in.nextInt();
            if(cont == 1){} 

    //escolha de armas
    int armaInt;
    String armaStr = null;
    System.out.println(nome + ", Você achou 4 objetos para ser usado como arma na sala, qual deseja pegar?");
    System.out.println("=====================");
    System.out.println("1- Notebook");
    System.out.println("2- Faca");
    System.out.println("3- Caneta");
    System.out.println("4- Lanterna");
    System.out.println("=====================");
        armaInt = in.nextInt();
    switch(armaInt){
        case 1:
        armaStr = "Notebook";
        armaInt = 50;
        break;
        
        case 2: 
        armaStr = "Faca";
        armaInt = 100;
        break;

        case 3:
        armaStr = "Caneta";
        armaInt = 25;
        break;

        case 4:
        armaStr = "Lanterna";
        armaInt = 75;
        break;
        
        default:
            System.out.print("Esse objeto não é uma arma.");
    }
    System.out.println("========================================================================");
    System.out.println("Então " + nome + ", Você está com " + hp[0] + " De vida, pegou uma " + armaStr + " e o dano dela é: " + armaInt);
    System.out.println("O que quer fazer agora?");
    System.out.println("1 - Lutar");
    System.out.println("2 - Fugir");
        escolha = in.nextInt();
    if(escolha == 1){
        while(hp[1] > 0){
        hp[1] = (hp[1] - armaInt);
            System.out.println("=========================================================================================");
            System.out.println("Você bateu no " + nomeInimigo[0] + " e ele ficou com " + hp[1] + " de vida.");
            System.out.println("Digite 1 para continuar");
            cont = in.nextInt();
            if(cont == 1){} 
        hp[0] = (hp[0] - dano[0]);
            System.out.println(nomeInimigo[0] + " devolveu com " + dano[0] + " e você ficou com: " + hp[0] + " de vida");
            System.out.println("Digite 1 para continuar");
            cont = in.nextInt();
            if(cont == 1){} 
        if(hp[1] < 0){
            System.out.println("Você matou ele!");
            System.out.println("=========================================================================================");          
        }
        }
        System.out.println("=========================================================================================");      
    }if(escolha == 2){
        System.out.println("Você escapou do "+nomeInimigo[0]+" mas no meio do caminho, encontrou com "+nomeInimigo[1]+" e ele está equipado com um grande slide em PowerPoint");            
        while(hp[2] > 0){
            System.out.println("=========================================================================================");
            System.out.println("Digite 1 para continuar");
            cont = in.nextInt();
            if(cont == 1){} 
            hp[2] = (hp[2] - armaInt);        
                System.out.println("Você usa o(a) " + armaStr + " nele, e da " + armaInt + " de dano nele, com isso ele fica com " + hp[2] + " de vida!");
                System.out.println("Digite 1 para continuar");
            cont = in.nextInt();
            if(cont == 1){} 
            hp[0] = (hp[0] - dano[1]);
                System.out.println(nomeInimigo[1] + " revida e você fica com " + hp[0] + " de Vida!");
                System.out.println("=========================================================================================");
                System.out.println("Digite 1 para continuar");
            cont = in.nextInt();
            if(cont == 1){} 
            if(hp[2] < 0){
                System.out.println("Você matou ele!");
            }
            }
            System.out.println("=========================================================================================");
            
            
        }
        
        
        System.out.println(nome + ", Você segue a sua trilha até encontrar com o " + nomeInimigo[3] + " Equipado com um poderoso arduino.");
        System.out.println(nomeInimigo[3] + " é imparável e te faz a seguinte pergunta com a chance de te deixar escapar do prédio: ");
        System.out.println("Qual o nome dado para a estrutura de repetição em java?");
            System.out.println("0 - Arrays");
            System.out.println("1 - For, while, do while");
            opcaoCerta = in.nextInt();
            
        if(opcaoCerta == 1){
            System.out.print("Você esta livre e salvo deste lugar!");
        }else{
            System.out.print("Você morreu!");
        }
    }
}
