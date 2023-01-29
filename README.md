# JAVA_METHOD_SUMMARY
자주 사용하는 메서드들을 한번에 찾아볼 수 있도록 정리한 레포지토리이다.    
정렬 순서는 따로 존재하지 않으며, ```Ctrl + F(찾기)``` 를 사용하여 해당 ```클래스.메서드```로 이동할 수 있다.

# 정리된 메서드 
## Arrays.METHOD
> Arrays.asList()<br>
> Arrays.sort(String[] a, Comparator<? super String> c)

## String.METHOD
> String.split(String regex)    
> String.isBlank()    
> String.replace(CharSequence target, CharSequence replacement)    
> String.replaceAll(String regex, String replacement)    
> String.substring(int beginIndex, int endIndex)    
> String.valueOf(char c)    
> String.toCharArray()    
> String.repeat(int count)    
> String.trim()    
> String.strip()    
> String.indent(int n)    
> String.indexOf(String str)    
> String.join(CharSequence delimiter, CharSequence... elements)    

## StringBuilder.METHOD
> StringBuilder.reverse()    
> StringBuilder.indexOf(String str)    
> StringBuilder.append(CharSequence s)    
> StringBuilder.append(String str)    

## StringJoiner.METHOD
> StringJoiner.add(CharSequence newElement)    

## Integer.METHOD
> Integer.valueOf(String s)    
> Integer.parseInt(String s)    
> Integer.compare(int x, int y)    
> Integer.min(int a, int b)    
> Integer.max(int a, int b)    
> Integer.parseUnsignedInt(String s)    
> Integer.toUnsignedLong(int x)    
> Integer.compareUnsigned(int x, int y)    
> Integer.remainderUnsigned(int dividend, int divisor)    
> Integer.divideUnsigned(int dividend, int divisor)    

## BigInteger.METHOD
> BigInteger.longValue()    
> BigInteger.intValue()    
> BigInteger.longValueExact()    
> BigInteger.intValueExact()    
> BigInteger.shortValueExact()    
> BigInteger.byteValueExact()    

## Map.METHOD
> Map.compute(Character key, BiFunction<? super Character, ? super Integer, ? extends Integer> remappingFunction)

## Math.METHOD
> Math.toIntExact(long value)    
> Math.floorDiv(int x, int y)    
> Math.floorMod(int x, int y)    
> Math.nextUp(double d)    
> Math.nextDown(double d)    
> Math.fma(double a, double b, double c)    
> Math.min(int a, int b)    
> Math.max(int a, int b)    
> Math.addExact(int x, int y)    

## Boolean.METHOD
> Boolean.logicalAnd(boolean a, boolean b)    
> Boolean.logicalOr(boolean a, boolean b)    
> Boolean.logicalXor(boolean a, boolean b)    

## Character.METHOD
> Character.isDigit(char ch)    

## Set.METHOD
> Set.contains(Object o)   

## Number.METHOD
> Number.shortValue()    
> Number.byteValue()    

## Short.METHOD
> Short.toUnsignedInt(short x)    

## Long.METHOD
> Long.parseLong(String s)    
> Long.parseUnsignedLong(String s)    

## Float.METHOD
> Float.parseFloat(String s)    

## IntStream.METHOD
> IntStream.range(int startInclusive, int endExclusive)    

## Enum.METHOD
> Enum.equals(Object other)    

## Comparator.METHOD
> Comparator.comparingInt(ToIntFunction<? super String> keyExtractor)    

## System.METHOD
> System.lineSeparator()    

## Stream.METHOD
> Stream.forEachOrdered(Consumer<? super String> action)    

## BiFunction.METHOD
> BiFunction.apply(Integer t, Integer u)    
    
    
[source](https://twitter.com/NoahhNim/status/1614474455119429632?s=20&t=JxagvwcFuLSsR1pkoL9Zzg,  "source")
