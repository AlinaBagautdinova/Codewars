# Codewars
Given a month as an integer from 1 to 12, return to which quarter of the year it belongs as an integer number.

public class Kata {
    public static int quarterOf(int month) {
      int k =0;
        if (month > 0 && month < 4) k = 1;
        if (month > 3 && month < 7) k = 2;
        if (month > 6 && month < 10) k = 3;
        if (month > 9 && month < 13) k = 4;
      return k;
    }
}
