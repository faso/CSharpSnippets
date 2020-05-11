# C# Snippets
C# code snippets I'd like not to lose

### UTC datetime printing
```
DateTime uDat = new DateTime(2009, 6, 15, 13, 45, 30,
                             DateTimeKind.Utc);
Console.WriteLine("{0} ({1}) --> {0:O}", uDat, uDat.Kind);

//    6/15/2009 1:45:30 PM (Utc) --> 2009-06-15T13:45:30.0000000Z
```
