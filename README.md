# Odd-Strings
in this Code it will give you those letters which are coming on the odd no. indexing
public class OddStrings {
    public OddStrings() {
    }

    public static void main(String[] args) {
        String[] arr = new String[]{"B", "H", "U", "M", "I", "K", "A"};

        for(int i = 0; i < arr.length; ++i) {
            if (i % 2 != 0) {
                System.out.println(arr[i]);
            }
        }

    }
}
