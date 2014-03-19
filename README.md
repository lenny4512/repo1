using System;
//The gravitational field of the Moon is approximately 17% of that on the Earth. Write a program that calculates the weight of a man on the moon by a given weight on the Earth. Examples:


class GravitationOnMoon
{
    static void Main()
    {
        double earthWeight = 86;
        double moonWeight = (earthWeight * 0.17);
        string kilos = "kg";
        Console.WriteLine("Earth weight of {0} {1} corresponds to moon weight: {2} {3} \n", earthWeight, kilos, moonWeight, kilos);


        double earthWeight2 = 74.6;
        double moonWeight2 = (earthWeight2 * 0.17);
        Console.WriteLine("Earth weight of {0} {1} corresponds to moon weight: {2} {3} \n", earthWeight2, kilos, moonWeight2, kilos);

        double earthWeight3 = 53.7;
        double moonWeight3 = (earthWeight3 * 0.17);
        Console.WriteLine("Earth weight of {0} {1} corresponds to moon weight: {2} {3} \n", earthWeight3, kilos, moonWeight3, kilos);
    }
}
