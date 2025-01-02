# java-simple-code

        public class Main {
        static void myMethod(String name, int age) {
        System.out.println(name + " " + age);
        }
        public static void main(String[] args) {
        int x = 12;
        double y = 12.34;
        //type casting
        int z = (int) y;
        float percentage = (float) y / z * 100;

        System.out.println("Print" + (x + y));
        System.out.println(z);
        System.out.println(percentage);
        String a = (x == 20) ? "good day" : "bad day"; //ternary operator
        System.out.println("Print " + a);
        for (int i = 0; i < 10; i++) {
            if (i == 4) {
                continue;
            }
            System.out.println(i);
        }
        //print the set and identify the value of length
        String[] cars = {"volvo", "BMW", "Honda", "Mazda", "Ford"};
        cars[0] = "Audi";
        System.out.println(cars.length);
        for (int i = 0; i < cars.length; i++) {
            System.out.println(cars[i]);
        }
        for (String car : cars) {
            System.out.println(car);
        }
        // print low number in a set
        int[] ages = {12, 34, 56, 78};
        float avg, sum = 0;
        int lowestage = ages[0];
        for (int age : ages) {
            if (age < lowestage) {
                lowestage = age;
            }
        }
        avg = sum / ages.length;
        System.out.println(avg);
        System.out.println(lowestage);
        int[][] mynumbers = {{1, 2, 2, 4}, {5, 6, 7, 8}};
        mynumbers[0][1] = 0;
        System.out.println(mynumbers[0][1]);

        int[][] number = {{1, 2, 2, 3, 4}, {7, 7, 9, 0}};
        for (int[] row : number) {
            for (int p : row) {
                System.out.println(p);
            }
        }
        //pyramid number print
        int num = 1;
        for (int i = 1; i < 5; i++) {
            for (int j = 0; j < i; j++) {
                System.out.print(num++);
            }
            System.out.println();
        }
        // * Pyramid print
        int l = 1;
        for (int i = 1; i < 5; i++) {
            for (int j = 0; j < 5 - i; j++) {
                System.out.print(" ");
            }
            for (int k = 0; k < (i * 2) + 2; k++) {
                if (k % 2 != 0) {
                    System.out.print(l++);
                } else {
                    System.out.print(" ");
                }

            }

            System.out.println(" ");
        }
        //call method with parameter
        myMethod("NITU" , 12);
        myMethod("Nipu" , 4);

        
        }
        }
