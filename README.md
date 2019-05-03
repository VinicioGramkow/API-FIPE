# API-FIPE

import FIPE.Metodos;

public class <NomeDaSuaClasse>{

  public static void main(String[] args) {
	  	Metodos met = new Metodos();
		  System.out.println(met.buscaMarcas());
		  System.out.println(met.buscarVeiculos(6));
		  System.out.println(met.buscarModelo(6, "4431"));
	  	System.out.println(met.consultar(6, "4431", "32000-1"));
	  }
  }
