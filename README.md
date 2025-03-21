// See https://aka.ms/new-console-template for more information
using System;
using System.Collections.Generic;
using System.Runtime.Serialization;
Console.WriteLine("Hello, World!");


Dictionary<string,List<double>> notaAluno = new Dictionary < string, List<int>>();
notaAluno.["Ze"] = new List<double> { 10, 8.5, 7.5 };
notaAluno.["Maria"] = new List<double> { 9.5, 8, 6.6 };

foreach ( var .aluno in notaAluno) 
{
    double soma = 0;
        for (int i = 0; i < notaAluno.Count; i++)
    {
        soma += aluno.Value[i];
    }
    double media = soma / aluno.Value.Count;
    Console.WriteLine($"media de {Aluno, Key}: {media}");
}
