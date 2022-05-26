Area of a circle using C#:

       double area,radius;
         Console.WriteLine("Enter a radius of your choice:");
         radius=Convert.ToDouble(Console.ReadLine());
         
         area= Math.PI * radius * radius;
         
         Console.WriteLine("Area of the circle with radius {0} is {1}",radius,area);
