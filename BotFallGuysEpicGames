import discord
from discord.ext import commands

 
import requests




import discord
from discord.ext import commands





bot = commands.Bot(command_prefix='!', help_command=None) #Comando
bot.remove_command("help") # Borra el comando por defecto !help










    
  
@bot.command()

async def fallguys(ctx):
    await ctx.message.delete()
    response = requests.get("https://jose89fcb.es/fallguysEPICGAMES/fallguys.php")
    fallguys = response.json()["Fallguys"]
    await ctx.send(f"{fallguys}")
  









@bot.event
async def on_ready():
    
    print("BOT listo!")


bot.run("") ## Consigue un TOKEN en: https://discord.com/developers/applications
