public class EmojiUnicodeCharacters {
    public static void main(String[] args) {

        String emoji = "😀";

        // Get the first code point of the emoji
        int codePoint = emoji.codePointAt(0);

        System.out.println("Emoji: " + emoji);
        System.out.println("Unicode: U+" + Integer.toHexString(codePoint).toUpperCase());
    }
}
