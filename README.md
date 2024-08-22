1. Unset the Global Configurations
git config --global --unset http.postbuffer
git config --global --unset http.version
git config --global --unset core.compression

git config --global --list


3. Set the Configurations Locally
cd path/to/aani-mobile
git config http.postBuffer 524288000
git config http.version HTTP/1.1
git config core.compression 9

4. Verify the Local Configurations
git config --local --list
