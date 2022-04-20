# Switch-lines-code_C-Sharp-VS  

(ES-es)    Comentar, quitar comentarios y cambiar líneas de código en Visual Studio Community C#.  
(EN-en)   Comment, Uncomment, and switch lines of code in Visual Studio Community C#.  
  
(ES-es)    -No he podido probarlo en otros entornos-  
(EN-en)   -I haven't been able to test it in other environments-  
  
(ES-es)    Copiar es codigo en Visual Studio.  
  		 En la primera línea en que aparece '//*//'  
  		 retirar una de las dos barras '/' del inicio, 
		 el código comentado se habrá descomentado  
		 comentándose el código activo.  
         para revertir, tan solo vuelve a añadir la barra '/'
		
(EN-en)	Copy the code into Visual Studio.  
  		On the first line where '//*//' appears  
		you remove one of the two '/' bars from the start, 
		the commented code will have been uncommented  
		commenting on the active code.  
        to revert, just add the '/' bar again
  
	namespace PruebaAlaternaInstrucciones.ProyectoAlternarInstrucciones
	{
		internal class PruebaAlternaInstrucciones
		{
			static void Main()
			{
				string? pruebaUno = "Prueba nº uno";
				string? pruebaDos = "Prueba nº dos";
				//*// Suprimir o añadir la primera "/" para alternar las siguientes instrucciones.
				/*/
				Console.Write($"Esta es la { pruebaUno} \t");
				/*/
				Console.WriteLine($"Esta es la { pruebaDos} \t");
				/*/
				Console.WriteLine($"Esta es la { pruebaDos} \n\r");
				/*/
				Console.WriteLine($"Esta es la { pruebaUno} \n\r");
				//*/
			}
		}
	}

