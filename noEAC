#include <iostream>
#include <Windows.h>


void launch() {
// gets the directory containing this exe
    char buffer[MAX_PATH];
    GetModuleFileName(NULL, buffer, MAX_PATH);

    std::string filePath(buffer);
    std::string directory = filePath.substr(0, filePath.find_last_of("\\/"));

    //std::string executablePath = directory + "\\armoredcore6.exe"; change this to whatever you need and uncomment

    char* commandLine = &executablePath[0];

//launches game with ShellExecute
    ShellExecute(NULL, "open", commandLine, NULL, NULL, SW_SHOWDEFAULT);
}


int main() {
    launch();
    return 0;
}
