interface Animal {
    void sound(); 
}
interface Mammal {
    void feed(); 
}
class Dog implements Animal, Mammal {
    public void sound() {
        System.out.println("Dog barks");
    }
    public void feed() {
        System.out.println("Dog feeds its puppies");
    }
}
public class Main {
    public static void main(String[] args) { 
        Dog dog = new Dog();
        dog.sound(); 
        dog.feed(); 
    }
}
output

Dog barks
Dog feeds its puppies
