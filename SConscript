'''
Author: Dyyt587 67887002+Dyyt587@users.noreply.github.com
Date: 2024-05-16 18:37:50
LastEditors: Dyyt587 67887002+Dyyt587@users.noreply.github.com
LastEditTime: 2024-05-16 19:16:55
FilePath: \undefinedc:\Users\80520\Documents\GitHub\24_robocon_code\project\packages\aUnity-latest\SConscript
Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
'''
Import('rtconfig')
from building import *
import os

cwd = GetCurrentDir()
src = Glob('**/*.c')
inc = [cwd]
inc += [cwd+"/acheck"]
inc += [cwd+"/alist"]
inc += [cwd+"/afifo"]
inc += [cwd+"/cvector"]


CXXFLAGS = ''


group = DefineGroup('aUnity', src, depend = ['PKG_USING_AUNITY'], CPPPATH = inc, CXXFLAGS = CXXFLAGS)

Return('group')
