    class HelloWorld {
    public static void main(String[] args) {
        int resto;
            for (int i = 1; i < 50; i++) {
                resto= i%2;
                if (resto==0) {
                System.out.println(i + " eh par");
                }else {
                System.out.println(i + " eh impar");
            }
        }
    }
}
