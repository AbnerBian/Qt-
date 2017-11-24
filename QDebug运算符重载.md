[QDebug](qdebug.html#QDebug) operator<<([QDebug](qdebug.html#QDebug) debug, const Coordinate &c)

```
  {
```

```
      QDebugStateSaver saver(debug);
```

```
      debug.nospace() << '(' << c.x() << ", " << c.y() << ')';
```

```

```

```
      return debug;
  }
```



qDebug()<<...<<后面的运算符不受前面状态的影响









