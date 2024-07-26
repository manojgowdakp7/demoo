class Animals {
    public static void main(String[] args) {
        System.out.println("Start main in Animals");

        String animal1 = "lion";
        String animal2 = "tiger";
        String animal3 = "elephant";
        String animal4 = "rhinoceros";
        String animal5 = "peacock";
        String animal6 = "gaur";
        String animal7 = "sloth bear";
        String animal8 = "Indian leopard";
        String animal9 = "Indian wolf";
        String animal10 = "Indian fox";
        String animal11 = "Indian pangolin";
        String animal12 = "Indian civet";
        String animal13 = "Indian giant squirrel";
        String animal14 = "Indian porcupine";
        String animal15 = "Indian mongoose";
        String animal16 = "Indian jackal";
        String animal17 = "Indian langur";
        String animal18 = "Indian hare";
        String animal19 = "Indian flying squirrel";
        String animal20 = "Indian wild boar";

        String[] animals = {
            animal1, animal2, animal3, animal4, animal5,
            animal6, animal7, animal8, animal9, animal10,
            animal11, animal12, animal13, animal14, animal15,
            animal16, animal17, animal18, animal19, animal20
        };

        for (int loop = animals.length-1; loop>=0; loop--) {
            String AnimalName = animals[loop];
            System.out.println("Animal Name: " + AnimalName);
        }

        int count = animals.length;
        System.out.println("Number of animals: " + count);

        System.out.println("End main in Animals");
    }
}
# demoo
