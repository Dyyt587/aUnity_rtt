Import('rtconfig')
from building import *
import os

cwd = GetCurrentDir()
src = Glob('**.c')
inc = [cwd]


CXXFLAGS = ''


group = DefineGroup('aUnity', src, depend = ['PKG_USING_AUNITY'], CPPPATH = inc, CXXFLAGS = CXXFLAGS)

Return('group')
