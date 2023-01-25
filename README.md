# JAVA_METHOD_SUMMARY
자주 사용하는 메서드들을 한번에 찾아볼 수 있도록 정리한 레포지토리이다.    
정렬 순서는 따로 존재하지 않으며, ```Ctrl + F(찾기)``` 를 사용하여 해당 ```클래스.메서드```로 이동할 수 있다.

# 정리된 메서드 
## Arrays.METHOD
Arrays.asList()<br>
Arrays.sort(String[] a, Comparator<? super String> c)<br>

## String.METHOD
String.split(String regex)<br>
String.isBlank()<br>
String.replace(CharSequence target, CharSequence replacement)<br>
String.replaceAll(String regex, String replacement)<br>
String.substring(int beginIndex, int endIndex)<br>
String.valueOf(char c)<br>
String.toCharArray()<br>
String.repeat(int count)<br>
String.trim()<br>
String.strip()<br>
String.indent(int n)<br>
String.indexOf(String str)<br>
String.join(CharSequence delimiter, CharSequence... elements)<br>

## StringBuilder.METHOD
StringBuilder.reverse()<br>
StringBuilder.indexOf(String str)<br>
StringBuilder.append(CharSequence s)<br>
StringBuilder.append(String str)<br>

## StringJoiner.METHOD
StringJoiner.add(CharSequence newElement)<br>

## Integer.METHOD
Integer.valueOf(String s)<br>
Integer.parseInt(String s)<br>
Integer.compare(int x, int y)<br>
Integer.min(int a, int b)<br>
Integer.max(int a, int b)<br>
Integer.parseUnsignedInt(String s)<br>
Integer.toUnsignedLong(int x)<br>
Integer.compareUnsigned(int x, int y)<br>
Integer.remainderUnsigned(int dividend, int divisor)<br>
Integer.divideUnsigned(int dividend, int divisor)<br>

## BigInteger.METHOD
BigInteger.longValue()<br>
BigInteger.intValue()<br>
BigInteger.longValueExact()<br>
BigInteger.intValueExact()<br>
BigInteger.shortValueExact()<br>
BigInteger.byteValueExact()<br>

## Map.METHOD
Map.compute(Character key, BiFunction<? super Character, ? super Integer, ? extends Integer> remappingFunction)

## Math.METHOD
Math.toIntExact(long value)<br>
Math.floorDiv(int x, int y)<br>
Math.floorMod(int x, int y)<br>
Math.nextUp(double d)<br>
Math.nextDown(double d)<br>
Math.fma(double a, double b, double c)<br>
Math.min(int a, int b)<br>
Math.max(int a, int b)<br>
Math.addExact(int x, int y)<br>

## Boolean.METHOD
Boolean.logicalAnd(boolean a, boolean b)<br>
Boolean.logicalOr(boolean a, boolean b)<br>
Boolean.logicalXor(boolean a, boolean b)<br>

## Character.METHOD
Character.isDigit(char ch)<br>

## Set.METHOD
Set.contains(Object o)<br>

## Number.METHOD
Number.shortValue()<br>
Number.byteValue()<br>

##Short.METHOD
Short.toUnsignedInt(short x)<br>

## Long.METHOD
Long.parseLong(String s)<br>
Long.parseUnsignedLong(String s)<br>

## Float.METHOD
Float.parseFloat(String s)<br>

## IntStream.METHOD
IntStream.range(int startInclusive, int endExclusive)<br>

## Enum.METHOD
Enum.equals(Object other)<br>

## Comparator.METHOD
Comparator.comparingInt(ToIntFunction<? super String> keyExtractor)<br>

## System.METHOD
System.lineSeparator()<br>

## Stream.METHOD
Stream.forEachOrdered(Consumer<? super String> action)<br>

## BiFunction.METHOD
BiFunction.apply(Integer t, Integer u)<br>
