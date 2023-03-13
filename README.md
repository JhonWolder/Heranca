class Main {
  public static void main(String[] args) {
    Cachorro c = new Cachorro();
    c.setNome ("Bidu");

    Gato g = new Gato();
    g.setNome("Lola"); 

    c.mostrar();
    g.mostrar();
    
  }
}




class Animal {
 private String nome;

  public void setNome(String n){
    nome = n;
}
  public String getNome(){
    return nome;
  }
public void Comer(){
  System.out.println("Eu gosto de comer.");
}
}



class Cachorro extends Animal {
  public void mostrar(){
    System.out.println("Meu nome é Bidu");
  }
}




class Gato extends Animal {
  public void mostrar(){
    System.out.println("Eu sou um gato");
  }
}
