import discord
from discord.ext import commands

clien = commands.Bot(command_prefix = '.')

@client.event
async def on_ready():
    print('Bot is ready.')
	
client.run('NDY4Mzc5NTI0NzY2MzY3NzQ0.XhJqJA.iRdWHcC6L71jTmNuTgJq8ddw8zE')
