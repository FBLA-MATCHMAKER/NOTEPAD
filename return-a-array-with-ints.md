class Main {

public static void main(String[] args) {

  System.out.println("Hello, World!");

  int inte[] = pass();

  for (int x = 0; x<3; x++) {

    System.out.println(inte[x]);

    System.out.println("THIS IS THE VALUE OF X" + x);

  }

}

public static int[] pass() {

int[] inte = new int[] {1, 3, 5};

return inte;

}

}
