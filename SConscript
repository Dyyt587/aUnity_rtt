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
