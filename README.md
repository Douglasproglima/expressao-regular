# expressao-regular

String com várias expressões regulares para uso no dia a dia.
=================

**Carga Horária Mensal, intervalo de 00:00 à 744:00**
public const string Carga_Horaria_Mensal = @"((0?0?\d|0?\d\d|[1-6]\d\d|7[0-4]\d|74[0-3])\:[0-5]\d)|(744\:00)";

**Carga Horária semanal, intervalo de 00:00 à 168:00**
* public const string Carga_Horaria_Semanal = @"((0?0?\d|0?\d\d|1[0-5]\d|16[0-7])\:[0-5]\d)|(168\:00)";
* public const string CEP_EditMask = @"(\d{2})\.(\d{3})\-(\d{3})";
* public const string CEP_MatchEvaluator = "$1.$2-$3";
* public const string CEP_Pattern = @"(\d{2})(\d{3})(\d{3})";

**Chave de Acesso Documentos Eletronicos**
* public const string CNPJ_EditMask = @"(\d{2})\.(\d{3})\.(\d{3})\/(\d{4})\-(\d{2})";
* public const string CNPJ_MatchEvaluator = "$1.$2.$3/$4-$5";
* public const string CNPJ_Pattern = @"(\d{2})(\d{3})(\d{3})(\d{4})(\d{2})";
* public const string CPF_EditMask = @"(\d{3})\.(\d{3})\.(\d{3})\-(\d{2})";
* public const string CPF_MatchEvaluator = "$1.$2.$3-$4";
* public const string CPF_Pattern = @"(\d{3})(\d{3})(\d{3})(\d{2})";
* public const string DayHour_EditMask = @"(([01]\d|2[0-3]):[0-5]\d)|24:00";

**Dias de Ferias Horas Semanais , intervalo de 00:00 à 44:00**
* public const string Dia_Ferias_HoraSemanal = @"((0?\d|[1-3]\d|4[0-3])\:[0-5]\d)|(44\:00)";
* public const string EMAIL_EditMask = @"\w+([-+.']\w+)*@\w+([-.]\w+)*\.\w+([-.]\w+)*";

**Quando utilizar um timespan e quiser visualizar e editar apenas a hora e o minuto**
* public const string HourMin_EditMask = @"(0?\d|1\d|2[0-3])\:[0-5]\d";
* public const string InscricaoEstadual_EditMask = @"(\d{3})\.(\d{3})\.(\d{3})\-(\d{4})";
* public const string InscricaoEstadual_MatchEvaluator = "$1.$2.$3-$4";
* public const string InscricaoEstadual_Pattern = @"(\d{3})(\d{3})(\d{3})(\d{4})";

**Não pode conter mais que três letras iguais consecutivas**
* public const string Nome_Pattern = "(A{4}|B{4}|C{4}|D{4}|E{4}|F{4}|G{4}|H{4}|I{4}|J{4}|K{4}|L{4}|M{4}|N{4}|O{4}|P{4}|Q{4}|R{4}|S{4}|T{4}|U{4}|V{4}|W{4}|X{4}|Y{4}|Z{4})";
public const string PHONE_EditMask = @"\(\d{2}\)\d?\d{4}\-\d{4}";
* public const string PHONE_MatchEvaluator = "($1)$2-$3";
* public const string PHONE_Pattern = @"(\d{2})(\d{4})(\d{4})";
* public const string PHONE_Pattern9Dig = @"(\d{2})(\d{5})(\d{4})";
