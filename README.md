# problem4
class Solution {
  public:
    pair<long long, long long> getMinMax(vector<long long int> arr) {
        // code here
        int minElement = *min_element(arr.begin(), arr.end());
    int maxElement = *max_element(arr.begin(), arr.end());

    // Return a vector containing the minimum and maximum elements
    return {minElement, maxElement};
    }
};
