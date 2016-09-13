# -MLPIII_CC_2016_2_LISTA-2
//Questão Ponto Extra

package br.com.unipe.lista2;
import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;

public class PrincipalTeste {

	public static <FormaGeometrica> void main(String[] args) {
		Retangulo fg1 = new Retangulo(3, 4);
	    Circulo fg2 = new Circulo(5);
	    System.out.println("Informe quantas formas deseja criar: ");
	    System.out.println("Deseja criar um quadrado: ");
	    System.out.println("Deseja criar um retangulo: ");
	    System.out.println("Deseja criar um quadrado: ");
	    System.out.println("Deseja criar um circulo: ");
	    List<FormaGeometrica> lista = new ArrayList<FormaGeometrica>();
	    boolean add = lista.add((FormaGeometrica) fg1);
	    boolean add2 = lista.add((FormaGeometrica) fg2);
	    for (FormaGeometrica fg : lista) {
	      System.out.println("Área da figura: " + ((Retangulo) fg).area());
	      System.out.println("Perímetro da figura: " + ((Retangulo) fg).perimetro());
	    }
	  }
	}
