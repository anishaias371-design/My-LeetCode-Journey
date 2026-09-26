class Solution {
    public int reverse(int n) {
        int rev = 0;
        boolean negative = n < 0;
        if(n < 0){
            n = -n;
        }
        while(n > 0){
            int last = n % 10;
        if(rev > 214748364){
            return 0;
        }
            rev = rev*10 + last;
            n = n/10;
        }
        if(negative){
            rev = -rev;
        }
        
        return rev;
        
    }
    
}
