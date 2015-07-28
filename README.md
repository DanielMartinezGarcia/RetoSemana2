# RetoSemana2
using System;

namespace RetoUno
{
	public class Reto2
	{
		public Reto2 ()
		{
			string radio = "";
			string altura = "";
			double volumen = 0;
			double area = 0;

			Console.WriteLine ("Escriba por favor el radio:");
			radio = Console.ReadLine ();
			double r = double.Parse (radio);

			Console.WriteLine ("Escriba por favor la altura:");
			altura = Console.ReadLine ();
			double a = double.Parse (altura);

			area = r * r * Math.PI;
			volumen = area * a;

			Console.WriteLine ("el area es: {0} y el volumen es {1}", area, volumen);
			Console.ReadKey ();



		}
	}
}
