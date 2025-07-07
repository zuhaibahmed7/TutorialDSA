import java.util.Arrays;

class Solution {
    public int[] sortArray(int[] nums) {
        Arrays.sort(nums);  
        return nums;
    }

    // Optional: For testing locally
    public static void main(String[] args) {
        Solution s = new Solution();
        int[] nums = {5, 2, 0, 1, 1};
        int[] sorted = s.sortArray(nums);

        // Print the result
        System.out.println(Arrays.toString(sorted));
    }
}
