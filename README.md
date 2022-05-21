# Switch-lines-code_C-Sharp-VS  
## https://developercommunity.visualstudio.com/t/Comment-and-uncomment-blocks-of-code-qui/513945?space=8&scope=follow

(ES-es)    Comentar, quitar comentarios y cambiar líneas de código en Visual Studio Community C#.  
(EN-en)   Comment, Uncomment, and switch lines of code in Visual Studio Community C#.  
  
(ES-es)    -No he podido probarlo en otros entornos-  
(EN-en)   -I haven't been able to test it in other environments-  
  
(ES-es)  ---------------------------------------------------------------------  
> Si llegas a usar los Comentarios Switch pon una copia de las instrucciones.  
> Aunque me fue aprobado e implantado hace ya 3 años, aún no es conocido.  
> ----------------------------------------------------------------------------  
> Uso de comentarios Switch para pruebas o colaboración:  
> formato:  
~~~~
>   //*// Autor de la modificación.  
>
>   Aquí va el código original sin cambios.  
>
>   /*/ // Motivo del cambio. (las dos barras del motivo son necesarias)  
>       // Si es necesario más de una línea,  
>       // ponerlas fuera del marcador. (con doble barra)  
>       // /* Y no usar comentarios multilínea */  
>
>   Aquí va el Código alternativo.  
>
>   //*/  
~~~~
> funcionamiento;  
>     Para ver u ocultar el código alternativo:  
>         quita o pon una de las dos // del inicio de la líneas con //*//  
  
(EN-en)  --------------------------------------------------------------------
> If you get to use the Switch Comments put a copy of the instructions.
> Although it was approved and implanted 3 years ago, it is not yet known.
> ---------------------------------------------------------------------------
> Using Switch feedback for testing or collaboration:
> format:
~~~~
> //*// Author of the modification.
> 
> Here is the original code unchanged.
> 
> /*/ // Reason for change. (the two bars of the motif are necessary)
>     // If more than one line is needed,
>     // put them off the scoreboard. (with double bar)
>     // /* And do not use multiline comments */
> 
> Here is the Alternative Code.
> 
> //*/
~~~~
> operation;
> To view or hide the alternate code:
> remove or put one of the two // from the start of the lines with //*//
 
 
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

