# codigoQuiniela
Resultados posibles de una quiniela en java
```java
public class Act01Quiniela {

  public static void main(String[] args) {
    // TODO Auto-generated method stub
	String numero;
	int cont1=0,cont2=0,cont3=0;
    int contador=0;
    for(int num1=1;num1<=3;num1++){
      for(int num2=1;num2<=3;num2++){
        for(int num3=1;num3<=3;num3++){
          for(int num4=1;num4<=3;num4++){
            for(int num5=1;num5<=3;num5++){
              for(int num6=1;num6<=3;num6++){
                for(int num7=1;num7<=3;num7++){
                  for(int num8=1;num8<=3;num8++){
                    for(int num9=1;num9<=3;num9++){
                      for(int num10=1;num10<=3;num10++){
                        for(int num11=1;num11<=3;num11++){
                          for(int num12=1;num12<=3;num12++){
                            for(int num13=1;num13<=3;num13++){
                              for(int num14=1;num14<=3;num14++){
                                numero=num1+""+num2+""+num3+""+num4+""+num5+""+num6+""+num7+""+num8+""+num9+""+num10+""+num11+""+num12+""+num13+""+num14;
                                cont1=0;cont2=0;cont3=0;
                                for (int i = 0; i < numero.length(); i++) {
									if (numero.charAt(i)=='1') 
										cont1++;
									else if (numero.charAt(i)=='2')
										cont2++;
									else
										cont3++;
									
									if ((cont1>5&&cont1<11)&&(cont2>2&&cont2<6)&&(cont3>3&&cont3<9)) {
										System.out.print(numero.replace("2", "x").replace("3", "2"));  
										contador++;
										System.out.println("--------------------"+contador);
									}
                                }
                              }
                            }
                          }
                        }
                      }
                    }
                  }
                }
              }
            }
          }
        }  
      }
    }
  }
}
```
