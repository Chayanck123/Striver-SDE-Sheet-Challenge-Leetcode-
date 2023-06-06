class Solution {
public:
    void setZeroes(vector<vector<int>>& matrix) {
        int rows = matrix.size();
        int col  = matrix[0].size();
        vector<int>zrows;
        vector<int>zcol;
        for(int i=0;i<rows;i++){
            for(int j=0;j<col;j++){
                if(matrix[i][j]==0){
                    zrows.push_back(i);
                    zcol.push_back(j);
                }
            }
        }
        for(int i=0;i<zrows.size();i++){
            for(int j=0;j<col;j++){
                matrix[zrows[i]][j] = 0;
            }
        }
        for(int i=0;i<zcol.size();i++){
            for(int j=0;j<rows;j++){
                matrix[j][zcol[i]] = 0;
            }
        }
    }
};
