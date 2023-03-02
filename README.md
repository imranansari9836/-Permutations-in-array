class Solution {
    public boolean isPossible(long a[], long b[], int n, long k) {
        // Your code goes here
        Arrays.sort(a);
        for(int i=0;i<n;i++)
        {
            if(a[i]+b[i]>=k)
            {
                return true;
            }
        }
        return false;
    }
}
