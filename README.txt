--the code

local loadstringsettings = {
	url='https://raw.githubusercontent.com/h9b/prison-life-kill/main/main.lua',
	load=true;
};

if loadstringsettings.load == true then
	loadstring(game:HttpGet(loadstringsettings.url))();
end;
