public class Main {
    public static void main(String[] args) {

                Scanner scanner = new Scanner(System.in);

                System.out.println("MENU:");
                System.out.println("1 - Dizer Olá");
                System.out.println("2 - Mostrar a data de hoje");
                System.out.println("3 - Sair");
                System.out.print("Escolha uma opção: ");

                int opcao = scanner.nextInt();

                if (opcao == 1) {
                    System.out.println("Olá!");
                } else if (opcao == 2) {
                    System.out.println("Hoje é dia 27/11/2025");
                } else if (opcao == 3) {
                    System.out.println("Saindo...");
                } else {
                    System.out.println("Opção inválida.");
                }

                scanner.close();
            }
        }
