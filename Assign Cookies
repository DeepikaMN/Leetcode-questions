// https://leetcode.com/problems/assign-cookies/?envType=daily-question&envId=2024-01-01

int findContentChildren(vector<int>& g, vector<int>& s) {
        sort(g.begin(), g.end());
        sort(s.begin(), s.end());
        
        int i = 0; // index for children
        int j = 0; // index for cookies
        int contentChildren = 0;
        
        while (i < g.size() && j < s.size()) {
            if (s[j] >= g[i]) {
                // Assign the cookie j to child i
                contentChildren++;
                i++; // Move to the next child
            }
            j++; // Move to the next cookie
        }
        
        return contentChildren;
    }
