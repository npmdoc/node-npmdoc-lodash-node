# api documentation for  [lodash-node (v3.10.2)](https://lodash.com/)  [![npm package](https://img.shields.io/npm/v/npmdoc-lodash-node.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-lodash-node) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-lodash-node.svg)](https://travis-ci.org/npmdoc/node-npmdoc-lodash-node)
#### Lodash module bundles for Node.js.

[![NPM](https://nodei.co/npm/lodash-node.png?downloads=true)](https://www.npmjs.com/package/lodash-node)

[![apidoc](https://npmdoc.github.io/node-npmdoc-lodash-node/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-lodash-node_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-lodash-node/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-lodash-node/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-lodash-node/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "John-David Dalton",
        "email": "john.david.dalton@gmail.com",
        "url": "http://allyoucanleet.com/"
    },
    "bugs": {
        "url": "https://github.com/lodash/lodash/issues"
    },
    "contributors": [
        {
            "name": "John-David Dalton",
            "email": "john.david.dalton@gmail.com",
            "url": "http://allyoucanleet.com/"
        },
        {
            "name": "Benjamin Tan",
            "email": "demoneaux@gmail.com",
            "url": "https://d10.github.io/"
        },
        {
            "name": "Blaine Bublitz",
            "email": "blaine@iceddev.com",
            "url": "http://www.iceddev.com/"
        },
        {
            "name": "Kit Cambridge",
            "email": "github@kitcambridge.be",
            "url": "http://kitcambridge.be/"
        },
        {
            "name": "Mathias Bynens",
            "email": "mathias@qiwi.be",
            "url": "https://mathiasbynens.be/"
        }
    ],
    "dependencies": {},
    "deprecated": "This package is discontinued. Use lodash@^4.0.0.",
    "description": "Lodash module bundles for Node.js.",
    "devDependencies": {},
    "directories": {},
    "dist": {
        "shasum": "2598d5b1b54e6a68b4cb544e5c730953cbf632f7",
        "tarball": "https://registry.npmjs.org/lodash-node/-/lodash-node-3.10.2.tgz"
    },
    "homepage": "https://lodash.com/",
    "icon": "https://lodash.com/icon.svg",
    "license": "MIT",
    "main": "modern/index.js",
    "maintainers": [
        {
            "name": "jdalton",
            "email": "john.david.dalton@gmail.com"
        },
        {
            "name": "mathias",
            "email": "mathias@qiwi.be"
        },
        {
            "name": "phated",
            "email": "blaine@iceddev.com"
        }
    ],
    "name": "lodash-node",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/lodash/lodash-node.git"
    },
    "scripts": {
        "test": "echo \"See https://travis-ci.org/lodash/lodash-cli for testing details.\""
    },
    "version": "3.10.2"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module lodash-node](#apidoc.module.lodash-node)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>_ (value)](#apidoc.element.lodash-node._)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>add (augend, addend)](#apidoc.element.lodash-node.add)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>after (n, func)](#apidoc.element.lodash-node.after)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>all (collection, predicate, thisArg)](#apidoc.element.lodash-node.all)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>any (collection, predicate, thisArg)](#apidoc.element.lodash-node.any)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>ary (func, n, guard)](#apidoc.element.lodash-node.ary)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>assign ()](#apidoc.element.lodash-node.assign)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>at ()](#apidoc.element.lodash-node.at)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>attempt ()](#apidoc.element.lodash-node.attempt)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>backflow ()](#apidoc.element.lodash-node.backflow)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>before (n, func)](#apidoc.element.lodash-node.before)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>bind ()](#apidoc.element.lodash-node.bind)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>bindAll ()](#apidoc.element.lodash-node.bindAll)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>bindKey ()](#apidoc.element.lodash-node.bindKey)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>callback (func, thisArg, guard)](#apidoc.element.lodash-node.callback)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>camelCase (string)](#apidoc.element.lodash-node.camelCase)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>capitalize (string)](#apidoc.element.lodash-node.capitalize)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>ceil (number, precision)](#apidoc.element.lodash-node.ceil)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>chain (value)](#apidoc.element.lodash-node.chain)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>chunk (array, size, guard)](#apidoc.element.lodash-node.chunk)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>clone (value, isDeep, customizer, thisArg)](#apidoc.element.lodash-node.clone)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>cloneDeep (value, customizer, thisArg)](#apidoc.element.lodash-node.cloneDeep)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>collect (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collect)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>compact (array)](#apidoc.element.lodash-node.compact)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>compose ()](#apidoc.element.lodash-node.compose)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>constant (value)](#apidoc.element.lodash-node.constant)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>contains (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.contains)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>countBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.countBy)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>create (prototype, properties, guard)](#apidoc.element.lodash-node.create)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>curry (func, arity, guard)](#apidoc.element.lodash-node.curry)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>curryRight (func, arity, guard)](#apidoc.element.lodash-node.curryRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>debounce (func, wait, options)](#apidoc.element.lodash-node.debounce)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>deburr (string)](#apidoc.element.lodash-node.deburr)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>defaults ()](#apidoc.element.lodash-node.defaults)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>defaultsDeep ()](#apidoc.element.lodash-node.defaultsDeep)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>defer ()](#apidoc.element.lodash-node.defer)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>delay ()](#apidoc.element.lodash-node.delay)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>detect (collection, predicate, thisArg)](#apidoc.element.lodash-node.detect)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>difference ()](#apidoc.element.lodash-node.difference)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>drop (array, n, guard)](#apidoc.element.lodash-node.drop)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>dropRight (array, n, guard)](#apidoc.element.lodash-node.dropRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>dropRightWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.dropRightWhile)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>dropWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.dropWhile)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>each (collection, iteratee, thisArg)](#apidoc.element.lodash-node.each)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>eachRight (collection, iteratee, thisArg)](#apidoc.element.lodash-node.eachRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>endsWith (string, target, position)](#apidoc.element.lodash-node.endsWith)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>eq (value, other, customizer, thisArg)](#apidoc.element.lodash-node.eq)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>escape (string)](#apidoc.element.lodash-node.escape)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>escapeRegExp (string)](#apidoc.element.lodash-node.escapeRegExp)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>every (collection, predicate, thisArg)](#apidoc.element.lodash-node.every)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>extend ()](#apidoc.element.lodash-node.extend)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>fill (array, value, start, end)](#apidoc.element.lodash-node.fill)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>filter (collection, predicate, thisArg)](#apidoc.element.lodash-node.filter)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>find (collection, predicate, thisArg)](#apidoc.element.lodash-node.find)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>findIndex (array, predicate, thisArg)](#apidoc.element.lodash-node.findIndex)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>findKey (object, predicate, thisArg)](#apidoc.element.lodash-node.findKey)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>findLast (collection, predicate, thisArg)](#apidoc.element.lodash-node.findLast)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>findLastIndex (array, predicate, thisArg)](#apidoc.element.lodash-node.findLastIndex)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>findLastKey (object, predicate, thisArg)](#apidoc.element.lodash-node.findLastKey)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>findWhere (collection, source)](#apidoc.element.lodash-node.findWhere)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>first (array)](#apidoc.element.lodash-node.first)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>flatten (array, isDeep, guard)](#apidoc.element.lodash-node.flatten)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>flattenDeep (array)](#apidoc.element.lodash-node.flattenDeep)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>floor (number, precision)](#apidoc.element.lodash-node.floor)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>flow ()](#apidoc.element.lodash-node.flow)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>flowRight ()](#apidoc.element.lodash-node.flowRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>foldl (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.foldl)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>foldr (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.foldr)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>forEach (collection, iteratee, thisArg)](#apidoc.element.lodash-node.forEach)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>forEachRight (collection, iteratee, thisArg)](#apidoc.element.lodash-node.forEachRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>forIn (object, iteratee, thisArg)](#apidoc.element.lodash-node.forIn)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>forInRight (object, iteratee, thisArg)](#apidoc.element.lodash-node.forInRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>forOwn (object, iteratee, thisArg)](#apidoc.element.lodash-node.forOwn)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>forOwnRight (object, iteratee, thisArg)](#apidoc.element.lodash-node.forOwnRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>functions (object)](#apidoc.element.lodash-node.functions)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>get (object, path, defaultValue)](#apidoc.element.lodash-node.get)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>groupBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.groupBy)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>gt (value, other)](#apidoc.element.lodash-node.gt)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>gte (value, other)](#apidoc.element.lodash-node.gte)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>has (object, path)](#apidoc.element.lodash-node.has)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>head (array)](#apidoc.element.lodash-node.head)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>identity (value)](#apidoc.element.lodash-node.identity)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>inRange (value, start, end)](#apidoc.element.lodash-node.inRange)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>include (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.include)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>includes (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.includes)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>indexBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.indexBy)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>indexOf (array, value, fromIndex)](#apidoc.element.lodash-node.indexOf)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>initial (array)](#apidoc.element.lodash-node.initial)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>inject (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.inject)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>intersection ()](#apidoc.element.lodash-node.intersection)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>invert (object, multiValue, guard)](#apidoc.element.lodash-node.invert)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>invoke ()](#apidoc.element.lodash-node.invoke)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isArguments (value)](#apidoc.element.lodash-node.isArguments)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isArray ()](#apidoc.element.lodash-node.isArray)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isBoolean (value)](#apidoc.element.lodash-node.isBoolean)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isDate (value)](#apidoc.element.lodash-node.isDate)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isElement (value)](#apidoc.element.lodash-node.isElement)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isEmpty (value)](#apidoc.element.lodash-node.isEmpty)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isEqual (value, other, customizer, thisArg)](#apidoc.element.lodash-node.isEqual)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isError (value)](#apidoc.element.lodash-node.isError)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isFinite (value)](#apidoc.element.lodash-node.isFinite)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isFunction (value)](#apidoc.element.lodash-node.isFunction)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isMatch (object, source, customizer, thisArg)](#apidoc.element.lodash-node.isMatch)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isNaN (value)](#apidoc.element.lodash-node.isNaN)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isNative (value)](#apidoc.element.lodash-node.isNative)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isNull (value)](#apidoc.element.lodash-node.isNull)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isNumber (value)](#apidoc.element.lodash-node.isNumber)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isObject (value)](#apidoc.element.lodash-node.isObject)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isPlainObject (value)](#apidoc.element.lodash-node.isPlainObject)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isRegExp (value)](#apidoc.element.lodash-node.isRegExp)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isString (value)](#apidoc.element.lodash-node.isString)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isTypedArray (value)](#apidoc.element.lodash-node.isTypedArray)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>isUndefined (value)](#apidoc.element.lodash-node.isUndefined)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>iteratee (func, thisArg, guard)](#apidoc.element.lodash-node.iteratee)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>kebabCase (string)](#apidoc.element.lodash-node.kebabCase)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>keys (object)](#apidoc.element.lodash-node.keys)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>keysIn (object)](#apidoc.element.lodash-node.keysIn)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>last (array)](#apidoc.element.lodash-node.last)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>lastIndexOf (array, value, fromIndex)](#apidoc.element.lodash-node.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>lt (value, other)](#apidoc.element.lodash-node.lt)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>lte (value, other)](#apidoc.element.lodash-node.lte)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>map (collection, iteratee, thisArg)](#apidoc.element.lodash-node.map)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>mapKeys (object, iteratee, thisArg)](#apidoc.element.lodash-node.mapKeys)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>mapValues (object, iteratee, thisArg)](#apidoc.element.lodash-node.mapValues)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>matches (source)](#apidoc.element.lodash-node.matches)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>matchesProperty (path, srcValue)](#apidoc.element.lodash-node.matchesProperty)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>max (collection, iteratee, thisArg)](#apidoc.element.lodash-node.max)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>memoize (func, resolver)](#apidoc.element.lodash-node.memoize)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>memoize.Cache ()](#apidoc.element.lodash-node.memoize.Cache)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>merge ()](#apidoc.element.lodash-node.merge)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>method ()](#apidoc.element.lodash-node.method)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>methodOf ()](#apidoc.element.lodash-node.methodOf)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>methods (object)](#apidoc.element.lodash-node.methods)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>min (collection, iteratee, thisArg)](#apidoc.element.lodash-node.min)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>mixin (object, source, options)](#apidoc.element.lodash-node.mixin)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>modArgs ()](#apidoc.element.lodash-node.modArgs)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>negate (predicate)](#apidoc.element.lodash-node.negate)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>noConflict ()](#apidoc.element.lodash-node.noConflict)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>noop ()](#apidoc.element.lodash-node.noop)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>now ()](#apidoc.element.lodash-node.now)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>object (props, values)](#apidoc.element.lodash-node.object)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>omit ()](#apidoc.element.lodash-node.omit)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>once (func)](#apidoc.element.lodash-node.once)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>pad (string, length, chars)](#apidoc.element.lodash-node.pad)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>padLeft (string, length, chars)](#apidoc.element.lodash-node.padLeft)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>padRight (string, length, chars)](#apidoc.element.lodash-node.padRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>pairs (object)](#apidoc.element.lodash-node.pairs)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>parseInt (string, radix, guard)](#apidoc.element.lodash-node.parseInt)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>partial ()](#apidoc.element.lodash-node.partial)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>partialRight ()](#apidoc.element.lodash-node.partialRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>partition (collection, iteratee, thisArg)](#apidoc.element.lodash-node.partition)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>pick ()](#apidoc.element.lodash-node.pick)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>pluck (collection, path)](#apidoc.element.lodash-node.pluck)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>property (path)](#apidoc.element.lodash-node.property)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>propertyOf (object)](#apidoc.element.lodash-node.propertyOf)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>pull ()](#apidoc.element.lodash-node.pull)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>pullAt ()](#apidoc.element.lodash-node.pullAt)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>random (min, max, floating)](#apidoc.element.lodash-node.random)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>range (start, end, step)](#apidoc.element.lodash-node.range)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>rearg ()](#apidoc.element.lodash-node.rearg)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>reduce (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.reduce)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>reduceRight (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.reduceRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>reject (collection, predicate, thisArg)](#apidoc.element.lodash-node.reject)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>remove (array, predicate, thisArg)](#apidoc.element.lodash-node.remove)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>repeat (string, n)](#apidoc.element.lodash-node.repeat)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>rest (array)](#apidoc.element.lodash-node.rest)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>restParam (func, start)](#apidoc.element.lodash-node.restParam)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>result (object, path, defaultValue)](#apidoc.element.lodash-node.result)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>round (number, precision)](#apidoc.element.lodash-node.round)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>runInContext (context)](#apidoc.element.lodash-node.runInContext)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>sample (collection, n, guard)](#apidoc.element.lodash-node.sample)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>select (collection, predicate, thisArg)](#apidoc.element.lodash-node.select)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>set (object, path, value)](#apidoc.element.lodash-node.set)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>shuffle (collection)](#apidoc.element.lodash-node.shuffle)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>size (collection)](#apidoc.element.lodash-node.size)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>slice (array, start, end)](#apidoc.element.lodash-node.slice)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>snakeCase (string)](#apidoc.element.lodash-node.snakeCase)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>some (collection, predicate, thisArg)](#apidoc.element.lodash-node.some)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>sortBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.sortBy)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>sortByAll ()](#apidoc.element.lodash-node.sortByAll)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>sortByOrder (collection, iteratees, orders, guard)](#apidoc.element.lodash-node.sortByOrder)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>sortedIndex (array, value, iteratee, thisArg)](#apidoc.element.lodash-node.sortedIndex)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>sortedLastIndex (array, value, iteratee, thisArg)](#apidoc.element.lodash-node.sortedLastIndex)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>spread (func)](#apidoc.element.lodash-node.spread)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>startCase (string)](#apidoc.element.lodash-node.startCase)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>startsWith (string, target, position)](#apidoc.element.lodash-node.startsWith)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>sum (collection, iteratee, thisArg)](#apidoc.element.lodash-node.sum)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>tail (array)](#apidoc.element.lodash-node.tail)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>take (array, n, guard)](#apidoc.element.lodash-node.take)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>takeRight (array, n, guard)](#apidoc.element.lodash-node.takeRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>takeRightWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.takeRightWhile)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>takeWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.takeWhile)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>tap (value, interceptor, thisArg)](#apidoc.element.lodash-node.tap)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>template (string, options, otherOptions)](#apidoc.element.lodash-node.template)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>throttle (func, wait, options)](#apidoc.element.lodash-node.throttle)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>thru (value, interceptor, thisArg)](#apidoc.element.lodash-node.thru)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>times (n, iteratee, thisArg)](#apidoc.element.lodash-node.times)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>toArray (value)](#apidoc.element.lodash-node.toArray)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>toPlainObject (value)](#apidoc.element.lodash-node.toPlainObject)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>transform (object, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.transform)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>trim (string, chars, guard)](#apidoc.element.lodash-node.trim)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>trimLeft (string, chars, guard)](#apidoc.element.lodash-node.trimLeft)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>trimRight (string, chars, guard)](#apidoc.element.lodash-node.trimRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>trunc (string, options, guard)](#apidoc.element.lodash-node.trunc)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>unescape (string)](#apidoc.element.lodash-node.unescape)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>union ()](#apidoc.element.lodash-node.union)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>uniq (array, isSorted, iteratee, thisArg)](#apidoc.element.lodash-node.uniq)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>unique (array, isSorted, iteratee, thisArg)](#apidoc.element.lodash-node.unique)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>uniqueId (prefix)](#apidoc.element.lodash-node.uniqueId)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>unzip (array)](#apidoc.element.lodash-node.unzip)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>unzipWith (array, iteratee, thisArg)](#apidoc.element.lodash-node.unzipWith)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>values (object)](#apidoc.element.lodash-node.values)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>valuesIn (object)](#apidoc.element.lodash-node.valuesIn)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>where (collection, source)](#apidoc.element.lodash-node.where)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>without ()](#apidoc.element.lodash-node.without)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>words (string, pattern, guard)](#apidoc.element.lodash-node.words)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>wrap (value, wrapper)](#apidoc.element.lodash-node.wrap)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>xor ()](#apidoc.element.lodash-node.xor)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>zip ()](#apidoc.element.lodash-node.zip)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>zipObject (props, values)](#apidoc.element.lodash-node.zipObject)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>zipWith ()](#apidoc.element.lodash-node.zipWith)
1.  object <span class="apidocSignatureSpan">lodash-node.</span>array
1.  object <span class="apidocSignatureSpan">lodash-node.</span>collection
1.  object <span class="apidocSignatureSpan">lodash-node.</span>date
1.  object <span class="apidocSignatureSpan">lodash-node.</span>function
1.  object <span class="apidocSignatureSpan">lodash-node.</span>lang
1.  object <span class="apidocSignatureSpan">lodash-node.</span>math
1.  object <span class="apidocSignatureSpan">lodash-node.</span>memoize.Cache.prototype
1.  object <span class="apidocSignatureSpan">lodash-node.</span>number
1.  object <span class="apidocSignatureSpan">lodash-node.</span>string
1.  object <span class="apidocSignatureSpan">lodash-node.</span>support
1.  object <span class="apidocSignatureSpan">lodash-node.</span>templateSettings
1.  object <span class="apidocSignatureSpan">lodash-node.</span>utility
1.  string <span class="apidocSignatureSpan">lodash-node.</span>VERSION

#### [module lodash-node.array](#apidoc.module.lodash-node.array)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>chunk (array, size, guard)](#apidoc.element.lodash-node.array.chunk)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>compact (array)](#apidoc.element.lodash-node.array.compact)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>difference ()](#apidoc.element.lodash-node.array.difference)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>drop (array, n, guard)](#apidoc.element.lodash-node.array.drop)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>dropRight (array, n, guard)](#apidoc.element.lodash-node.array.dropRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>dropRightWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.array.dropRightWhile)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>dropWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.array.dropWhile)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>fill (array, value, start, end)](#apidoc.element.lodash-node.array.fill)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>findIndex (array, predicate, thisArg)](#apidoc.element.lodash-node.array.findIndex)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>findLastIndex (array, predicate, thisArg)](#apidoc.element.lodash-node.array.findLastIndex)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>first (array)](#apidoc.element.lodash-node.array.first)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>flatten (array, isDeep, guard)](#apidoc.element.lodash-node.array.flatten)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>flattenDeep (array)](#apidoc.element.lodash-node.array.flattenDeep)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>head (array)](#apidoc.element.lodash-node.array.head)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>indexOf (array, value, fromIndex)](#apidoc.element.lodash-node.array.indexOf)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>initial (array)](#apidoc.element.lodash-node.array.initial)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>intersection ()](#apidoc.element.lodash-node.array.intersection)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>last (array)](#apidoc.element.lodash-node.array.last)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>lastIndexOf (array, value, fromIndex)](#apidoc.element.lodash-node.array.lastIndexOf)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>object (props, values)](#apidoc.element.lodash-node.array.object)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>pull ()](#apidoc.element.lodash-node.array.pull)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>pullAt ()](#apidoc.element.lodash-node.array.pullAt)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>remove (array, predicate, thisArg)](#apidoc.element.lodash-node.array.remove)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>rest (array)](#apidoc.element.lodash-node.array.rest)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>slice (array, start, end)](#apidoc.element.lodash-node.array.slice)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>sortedIndex (array, value, iteratee, thisArg)](#apidoc.element.lodash-node.array.sortedIndex)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>sortedLastIndex (array, value, iteratee, thisArg)](#apidoc.element.lodash-node.array.sortedLastIndex)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>tail (array)](#apidoc.element.lodash-node.array.tail)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>take (array, n, guard)](#apidoc.element.lodash-node.array.take)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>takeRight (array, n, guard)](#apidoc.element.lodash-node.array.takeRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>takeRightWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.array.takeRightWhile)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>takeWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.array.takeWhile)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>union ()](#apidoc.element.lodash-node.array.union)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>uniq (array, isSorted, iteratee, thisArg)](#apidoc.element.lodash-node.array.uniq)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>unique (array, isSorted, iteratee, thisArg)](#apidoc.element.lodash-node.array.unique)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>unzip (array)](#apidoc.element.lodash-node.array.unzip)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>unzipWith (array, iteratee, thisArg)](#apidoc.element.lodash-node.array.unzipWith)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>without ()](#apidoc.element.lodash-node.array.without)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>xor ()](#apidoc.element.lodash-node.array.xor)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>zip ()](#apidoc.element.lodash-node.array.zip)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>zipObject (props, values)](#apidoc.element.lodash-node.array.zipObject)
1.  [function <span class="apidocSignatureSpan">lodash-node.array.</span>zipWith ()](#apidoc.element.lodash-node.array.zipWith)

#### [module lodash-node.bind](#apidoc.module.lodash-node.bind)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>bind ()](#apidoc.element.lodash-node.bind.bind)
1.  [function <span class="apidocSignatureSpan">lodash-node.bind.</span>placeholder (value)](#apidoc.element.lodash-node.bind.placeholder)

#### [module lodash-node.bindKey](#apidoc.module.lodash-node.bindKey)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>bindKey ()](#apidoc.element.lodash-node.bindKey.bindKey)
1.  [function <span class="apidocSignatureSpan">lodash-node.bindKey.</span>placeholder (value)](#apidoc.element.lodash-node.bindKey.placeholder)

#### [module lodash-node.chain](#apidoc.module.lodash-node.chain)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>chain (value)](#apidoc.element.lodash-node.chain.chain)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>commit ()](#apidoc.element.lodash-node.chain.commit)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>concat ()](#apidoc.element.lodash-node.chain.concat)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>lodash (value)](#apidoc.element.lodash-node.chain.lodash)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>plant (value)](#apidoc.element.lodash-node.chain.plant)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>reverse ()](#apidoc.element.lodash-node.chain.reverse)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>run ()](#apidoc.element.lodash-node.chain.run)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>tap (value, interceptor, thisArg)](#apidoc.element.lodash-node.chain.tap)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>thru (value, interceptor, thisArg)](#apidoc.element.lodash-node.chain.thru)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>toJSON ()](#apidoc.element.lodash-node.chain.toJSON)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>toString ()](#apidoc.element.lodash-node.chain.toString)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>value ()](#apidoc.element.lodash-node.chain.value)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>valueOf ()](#apidoc.element.lodash-node.chain.valueOf)
1.  [function <span class="apidocSignatureSpan">lodash-node.chain.</span>wrapperChain ()](#apidoc.element.lodash-node.chain.wrapperChain)

#### [module lodash-node.collection](#apidoc.module.lodash-node.collection)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>all (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.all)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>any (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.any)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>at ()](#apidoc.element.lodash-node.collection.at)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>collect (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.collect)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>contains (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.collection.contains)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>countBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.countBy)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>detect (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.detect)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>each (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.each)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>eachRight (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.eachRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>every (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.every)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>filter (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.filter)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>find (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.find)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>findLast (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.findLast)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>findWhere (collection, source)](#apidoc.element.lodash-node.collection.findWhere)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>foldl (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.collection.foldl)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>foldr (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.collection.foldr)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>forEach (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.forEach)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>forEachRight (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.forEachRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>groupBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.groupBy)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>include (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.collection.include)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>includes (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.collection.includes)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>indexBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.indexBy)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>inject (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.collection.inject)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>invoke ()](#apidoc.element.lodash-node.collection.invoke)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>map (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.map)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>max (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.max)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>min (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.min)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>partition (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.partition)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>pluck (collection, path)](#apidoc.element.lodash-node.collection.pluck)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>reduce (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.collection.reduce)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>reduceRight (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.collection.reduceRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>reject (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.reject)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>sample (collection, n, guard)](#apidoc.element.lodash-node.collection.sample)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>select (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.select)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>shuffle (collection)](#apidoc.element.lodash-node.collection.shuffle)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>size (collection)](#apidoc.element.lodash-node.collection.size)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>some (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.some)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>sortBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.sortBy)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>sortByAll ()](#apidoc.element.lodash-node.collection.sortByAll)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>sortByOrder (collection, iteratees, orders, guard)](#apidoc.element.lodash-node.collection.sortByOrder)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>sum (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.sum)
1.  [function <span class="apidocSignatureSpan">lodash-node.collection.</span>where (collection, source)](#apidoc.element.lodash-node.collection.where)

#### [module lodash-node.curry](#apidoc.module.lodash-node.curry)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>curry (func, arity, guard)](#apidoc.element.lodash-node.curry.curry)
1.  [function <span class="apidocSignatureSpan">lodash-node.curry.</span>placeholder (value)](#apidoc.element.lodash-node.curry.placeholder)

#### [module lodash-node.curryRight](#apidoc.module.lodash-node.curryRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>curryRight (func, arity, guard)](#apidoc.element.lodash-node.curryRight.curryRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.curryRight.</span>placeholder (value)](#apidoc.element.lodash-node.curryRight.placeholder)

#### [module lodash-node.date](#apidoc.module.lodash-node.date)
1.  [function <span class="apidocSignatureSpan">lodash-node.date.</span>now ()](#apidoc.element.lodash-node.date.now)

#### [module lodash-node.function](#apidoc.module.lodash-node.function)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>after (n, func)](#apidoc.element.lodash-node.function.after)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>ary (func, n, guard)](#apidoc.element.lodash-node.function.ary)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>backflow ()](#apidoc.element.lodash-node.function.backflow)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>before (n, func)](#apidoc.element.lodash-node.function.before)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>bind ()](#apidoc.element.lodash-node.function.bind)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>bindAll ()](#apidoc.element.lodash-node.function.bindAll)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>bindKey ()](#apidoc.element.lodash-node.function.bindKey)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>compose ()](#apidoc.element.lodash-node.function.compose)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>curry (func, arity, guard)](#apidoc.element.lodash-node.function.curry)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>curryRight (func, arity, guard)](#apidoc.element.lodash-node.function.curryRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>debounce (func, wait, options)](#apidoc.element.lodash-node.function.debounce)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>defer ()](#apidoc.element.lodash-node.function.defer)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>delay ()](#apidoc.element.lodash-node.function.delay)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>flow ()](#apidoc.element.lodash-node.function.flow)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>flowRight ()](#apidoc.element.lodash-node.function.flowRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>memoize (func, resolver)](#apidoc.element.lodash-node.function.memoize)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>modArgs ()](#apidoc.element.lodash-node.function.modArgs)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>negate (predicate)](#apidoc.element.lodash-node.function.negate)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>once (func)](#apidoc.element.lodash-node.function.once)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>partial ()](#apidoc.element.lodash-node.function.partial)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>partialRight ()](#apidoc.element.lodash-node.function.partialRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>rearg ()](#apidoc.element.lodash-node.function.rearg)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>restParam (func, start)](#apidoc.element.lodash-node.function.restParam)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>spread (func)](#apidoc.element.lodash-node.function.spread)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>throttle (func, wait, options)](#apidoc.element.lodash-node.function.throttle)
1.  [function <span class="apidocSignatureSpan">lodash-node.function.</span>wrap (value, wrapper)](#apidoc.element.lodash-node.function.wrap)

#### [module lodash-node.lang](#apidoc.module.lodash-node.lang)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>clone (value, isDeep, customizer, thisArg)](#apidoc.element.lodash-node.lang.clone)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>cloneDeep (value, customizer, thisArg)](#apidoc.element.lodash-node.lang.cloneDeep)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>eq (value, other, customizer, thisArg)](#apidoc.element.lodash-node.lang.eq)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>gt (value, other)](#apidoc.element.lodash-node.lang.gt)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>gte (value, other)](#apidoc.element.lodash-node.lang.gte)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isArguments (value)](#apidoc.element.lodash-node.lang.isArguments)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isArray ()](#apidoc.element.lodash-node.lang.isArray)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isBoolean (value)](#apidoc.element.lodash-node.lang.isBoolean)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isDate (value)](#apidoc.element.lodash-node.lang.isDate)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isElement (value)](#apidoc.element.lodash-node.lang.isElement)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isEmpty (value)](#apidoc.element.lodash-node.lang.isEmpty)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isEqual (value, other, customizer, thisArg)](#apidoc.element.lodash-node.lang.isEqual)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isError (value)](#apidoc.element.lodash-node.lang.isError)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isFinite (value)](#apidoc.element.lodash-node.lang.isFinite)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isFunction (value)](#apidoc.element.lodash-node.lang.isFunction)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isMatch (object, source, customizer, thisArg)](#apidoc.element.lodash-node.lang.isMatch)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isNaN (value)](#apidoc.element.lodash-node.lang.isNaN)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isNative (value)](#apidoc.element.lodash-node.lang.isNative)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isNull (value)](#apidoc.element.lodash-node.lang.isNull)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isNumber (value)](#apidoc.element.lodash-node.lang.isNumber)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isObject (value)](#apidoc.element.lodash-node.lang.isObject)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isPlainObject (value)](#apidoc.element.lodash-node.lang.isPlainObject)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isRegExp (value)](#apidoc.element.lodash-node.lang.isRegExp)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isString (value)](#apidoc.element.lodash-node.lang.isString)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isTypedArray (value)](#apidoc.element.lodash-node.lang.isTypedArray)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>isUndefined (value)](#apidoc.element.lodash-node.lang.isUndefined)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>lt (value, other)](#apidoc.element.lodash-node.lang.lt)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>lte (value, other)](#apidoc.element.lodash-node.lang.lte)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>toArray (value)](#apidoc.element.lodash-node.lang.toArray)
1.  [function <span class="apidocSignatureSpan">lodash-node.lang.</span>toPlainObject (value)](#apidoc.element.lodash-node.lang.toPlainObject)

#### [module lodash-node.math](#apidoc.module.lodash-node.math)
1.  [function <span class="apidocSignatureSpan">lodash-node.math.</span>add (augend, addend)](#apidoc.element.lodash-node.math.add)
1.  [function <span class="apidocSignatureSpan">lodash-node.math.</span>ceil (number, precision)](#apidoc.element.lodash-node.math.ceil)
1.  [function <span class="apidocSignatureSpan">lodash-node.math.</span>floor (number, precision)](#apidoc.element.lodash-node.math.floor)
1.  [function <span class="apidocSignatureSpan">lodash-node.math.</span>max (collection, iteratee, thisArg)](#apidoc.element.lodash-node.math.max)
1.  [function <span class="apidocSignatureSpan">lodash-node.math.</span>min (collection, iteratee, thisArg)](#apidoc.element.lodash-node.math.min)
1.  [function <span class="apidocSignatureSpan">lodash-node.math.</span>round (number, precision)](#apidoc.element.lodash-node.math.round)
1.  [function <span class="apidocSignatureSpan">lodash-node.math.</span>sum (collection, iteratee, thisArg)](#apidoc.element.lodash-node.math.sum)

#### [module lodash-node.memoize](#apidoc.module.lodash-node.memoize)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>memoize (func, resolver)](#apidoc.element.lodash-node.memoize.memoize)
1.  [function <span class="apidocSignatureSpan">lodash-node.memoize.</span>Cache ()](#apidoc.element.lodash-node.memoize.Cache)

#### [module lodash-node.memoize.Cache](#apidoc.module.lodash-node.memoize.Cache)
1.  [function <span class="apidocSignatureSpan">lodash-node.memoize.</span>Cache ()](#apidoc.element.lodash-node.memoize.Cache.Cache)

#### [module lodash-node.memoize.Cache.prototype](#apidoc.module.lodash-node.memoize.Cache.prototype)
1.  [function <span class="apidocSignatureSpan">lodash-node.memoize.Cache.prototype.</span>delete (key)](#apidoc.element.lodash-node.memoize.Cache.prototype.delete)
1.  [function <span class="apidocSignatureSpan">lodash-node.memoize.Cache.prototype.</span>get (key)](#apidoc.element.lodash-node.memoize.Cache.prototype.get)
1.  [function <span class="apidocSignatureSpan">lodash-node.memoize.Cache.prototype.</span>has (key)](#apidoc.element.lodash-node.memoize.Cache.prototype.has)
1.  [function <span class="apidocSignatureSpan">lodash-node.memoize.Cache.prototype.</span>set (key, value)](#apidoc.element.lodash-node.memoize.Cache.prototype.set)

#### [module lodash-node.number](#apidoc.module.lodash-node.number)
1.  [function <span class="apidocSignatureSpan">lodash-node.number.</span>inRange (value, start, end)](#apidoc.element.lodash-node.number.inRange)
1.  [function <span class="apidocSignatureSpan">lodash-node.number.</span>random (min, max, floating)](#apidoc.element.lodash-node.number.random)

#### [module lodash-node.object](#apidoc.module.lodash-node.object)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>assign ()](#apidoc.element.lodash-node.object.assign)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>create (prototype, properties, guard)](#apidoc.element.lodash-node.object.create)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>defaults ()](#apidoc.element.lodash-node.object.defaults)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>defaultsDeep ()](#apidoc.element.lodash-node.object.defaultsDeep)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>extend ()](#apidoc.element.lodash-node.object.extend)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>findKey (object, predicate, thisArg)](#apidoc.element.lodash-node.object.findKey)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>findLastKey (object, predicate, thisArg)](#apidoc.element.lodash-node.object.findLastKey)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>forIn (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.forIn)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>forInRight (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.forInRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>forOwn (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.forOwn)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>forOwnRight (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.forOwnRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>functions (object)](#apidoc.element.lodash-node.object.functions)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>get (object, path, defaultValue)](#apidoc.element.lodash-node.object.get)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>has (object, path)](#apidoc.element.lodash-node.object.has)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>invert (object, multiValue, guard)](#apidoc.element.lodash-node.object.invert)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>keys (object)](#apidoc.element.lodash-node.object.keys)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>keysIn (object)](#apidoc.element.lodash-node.object.keysIn)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>mapKeys (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.mapKeys)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>mapValues (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.mapValues)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>merge ()](#apidoc.element.lodash-node.object.merge)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>methods (object)](#apidoc.element.lodash-node.object.methods)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>omit ()](#apidoc.element.lodash-node.object.omit)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>pairs (object)](#apidoc.element.lodash-node.object.pairs)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>pick ()](#apidoc.element.lodash-node.object.pick)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>result (object, path, defaultValue)](#apidoc.element.lodash-node.object.result)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>set (object, path, value)](#apidoc.element.lodash-node.object.set)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>transform (object, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.object.transform)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>values (object)](#apidoc.element.lodash-node.object.values)
1.  [function <span class="apidocSignatureSpan">lodash-node.object.</span>valuesIn (object)](#apidoc.element.lodash-node.object.valuesIn)

#### [module lodash-node.partial](#apidoc.module.lodash-node.partial)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>partial ()](#apidoc.element.lodash-node.partial.partial)
1.  [function <span class="apidocSignatureSpan">lodash-node.partial.</span>placeholder (value)](#apidoc.element.lodash-node.partial.placeholder)

#### [module lodash-node.partialRight](#apidoc.module.lodash-node.partialRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.</span>partialRight ()](#apidoc.element.lodash-node.partialRight.partialRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.partialRight.</span>placeholder (value)](#apidoc.element.lodash-node.partialRight.placeholder)

#### [module lodash-node.string](#apidoc.module.lodash-node.string)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>camelCase (string)](#apidoc.element.lodash-node.string.camelCase)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>capitalize (string)](#apidoc.element.lodash-node.string.capitalize)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>deburr (string)](#apidoc.element.lodash-node.string.deburr)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>endsWith (string, target, position)](#apidoc.element.lodash-node.string.endsWith)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>escape (string)](#apidoc.element.lodash-node.string.escape)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>escapeRegExp (string)](#apidoc.element.lodash-node.string.escapeRegExp)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>kebabCase (string)](#apidoc.element.lodash-node.string.kebabCase)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>pad (string, length, chars)](#apidoc.element.lodash-node.string.pad)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>padLeft (string, length, chars)](#apidoc.element.lodash-node.string.padLeft)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>padRight (string, length, chars)](#apidoc.element.lodash-node.string.padRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>parseInt (string, radix, guard)](#apidoc.element.lodash-node.string.parseInt)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>repeat (string, n)](#apidoc.element.lodash-node.string.repeat)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>snakeCase (string)](#apidoc.element.lodash-node.string.snakeCase)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>startCase (string)](#apidoc.element.lodash-node.string.startCase)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>startsWith (string, target, position)](#apidoc.element.lodash-node.string.startsWith)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>template (string, options, otherOptions)](#apidoc.element.lodash-node.string.template)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>trim (string, chars, guard)](#apidoc.element.lodash-node.string.trim)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>trimLeft (string, chars, guard)](#apidoc.element.lodash-node.string.trimLeft)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>trimRight (string, chars, guard)](#apidoc.element.lodash-node.string.trimRight)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>trunc (string, options, guard)](#apidoc.element.lodash-node.string.trunc)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>unescape (string)](#apidoc.element.lodash-node.string.unescape)
1.  [function <span class="apidocSignatureSpan">lodash-node.string.</span>words (string, pattern, guard)](#apidoc.element.lodash-node.string.words)
1.  object <span class="apidocSignatureSpan">lodash-node.string.</span>templateSettings

#### [module lodash-node.utility](#apidoc.module.lodash-node.utility)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>attempt ()](#apidoc.element.lodash-node.utility.attempt)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>callback (func, thisArg, guard)](#apidoc.element.lodash-node.utility.callback)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>constant (value)](#apidoc.element.lodash-node.utility.constant)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>identity (value)](#apidoc.element.lodash-node.utility.identity)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>iteratee (func, thisArg, guard)](#apidoc.element.lodash-node.utility.iteratee)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>matches (source)](#apidoc.element.lodash-node.utility.matches)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>matchesProperty (path, srcValue)](#apidoc.element.lodash-node.utility.matchesProperty)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>method ()](#apidoc.element.lodash-node.utility.method)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>methodOf ()](#apidoc.element.lodash-node.utility.methodOf)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>mixin (object, source, options)](#apidoc.element.lodash-node.utility.mixin)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>noop ()](#apidoc.element.lodash-node.utility.noop)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>property (path)](#apidoc.element.lodash-node.utility.property)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>propertyOf (object)](#apidoc.element.lodash-node.utility.propertyOf)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>range (start, end, step)](#apidoc.element.lodash-node.utility.range)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>times (n, iteratee, thisArg)](#apidoc.element.lodash-node.utility.times)
1.  [function <span class="apidocSignatureSpan">lodash-node.utility.</span>uniqueId (prefix)](#apidoc.element.lodash-node.utility.uniqueId)



# <a name="apidoc.module.lodash-node"></a>[module lodash-node](#apidoc.module.lodash-node)

#### <a name="apidoc.element.lodash-node._"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>_ (value)](#apidoc.element.lodash-node._)
- description and source-code
```javascript
function lodash(value) {
  if (isObjectLike(value) && !isArray(value) && !(value instanceof LazyWrapper)) {
    if (value instanceof LodashWrapper) {
      return value;
    }
    if (hasOwnProperty.call(value, '__chain__') && hasOwnProperty.call(value, '__wrapped__')) {
      return wrapperClone(value);
    }
  }
  return new LodashWrapper(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.add"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>add (augend, addend)](#apidoc.element.lodash-node.add)
- description and source-code
```javascript
function add(augend, addend) {
  return (+augend || 0) + (+addend || 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.after"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>after (n, func)](#apidoc.element.lodash-node.after)
- description and source-code
```javascript
function after(n, func) {
  if (typeof func != 'function') {
    if (typeof n == 'function') {
      var temp = n;
      n = func;
      func = temp;
    } else {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
  }
  n = nativeIsFinite(n = +n) ? n : 0;
  return function() {
    if (--n < 1) {
      return func.apply(this, arguments);
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.all"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>all (collection, predicate, thisArg)](#apidoc.element.lodash-node.all)
- description and source-code
```javascript
function every(collection, predicate, thisArg) {
  var func = isArray(collection) ? arrayEvery : baseEvery;
  if (thisArg && isIterateeCall(collection, predicate, thisArg)) {
    predicate = undefined;
  }
  if (typeof predicate != 'function' || thisArg !== undefined) {
    predicate = getCallback(predicate, thisArg, 3);
  }
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.any"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>any (collection, predicate, thisArg)](#apidoc.element.lodash-node.any)
- description and source-code
```javascript
function some(collection, predicate, thisArg) {
  var func = isArray(collection) ? arraySome : baseSome;
  if (thisArg && isIterateeCall(collection, predicate, thisArg)) {
    predicate = undefined;
  }
  if (typeof predicate != 'function' || thisArg !== undefined) {
    predicate = getCallback(predicate, thisArg, 3);
  }
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.ary"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>ary (func, n, guard)](#apidoc.element.lodash-node.ary)
- description and source-code
```javascript
function ary(func, n, guard) {
  if (guard && isIterateeCall(func, n, guard)) {
    n = undefined;
  }
  n = (func && n == null) ? func.length : nativeMax(+n || 0, 0);
  return createWrapper(func, ARY_FLAG, undefined, undefined, undefined, undefined, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.assign"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>assign ()](#apidoc.element.lodash-node.assign)
- description and source-code
```javascript
assign = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.at"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>at ()](#apidoc.element.lodash-node.at)
- description and source-code
```javascript
at = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.attempt"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>attempt ()](#apidoc.element.lodash-node.attempt)
- description and source-code
```javascript
attempt = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.backflow"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>backflow ()](#apidoc.element.lodash-node.backflow)
- description and source-code
```javascript
backflow = function () {
  var wrapper,
      length = arguments.length,
      index = fromRight ? length : -1,
      leftIndex = 0,
      funcs = Array(length);

  while ((fromRight ? index-- : ++index < length)) {
    var func = funcs[leftIndex++] = arguments[index];
    if (typeof func != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    if (!wrapper && LodashWrapper.prototype.thru && getFuncName(func) == 'wrapper') {
      wrapper = new LodashWrapper([], true);
    }
  }
  index = wrapper ? -1 : length;
  while (++index < length) {
    func = funcs[index];

    var funcName = getFuncName(func),
        data = funcName == 'wrapper' ? getData(func) : undefined;

    if (data && isLaziable(data[0]) && data[1] == (ARY_FLAG | CURRY_FLAG | PARTIAL_FLAG | REARG_FLAG) && !data[4].length && data
[9] == 1) {
      wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
    } else {
      wrapper = (func.length == 1 && isLaziable(func)) ? wrapper[funcName]() : wrapper.thru(func);
    }
  }
  return function() {
    var args = arguments,
        value = args[0];

    if (wrapper && args.length == 1 && isArray(value) && value.length >= LARGE_ARRAY_SIZE) {
      return wrapper.plant(value).value();
    }
    var index = 0,
        result = length ? funcs[index].apply(this, args) : value;

    while (++index < length) {
      result = funcs[index].call(this, result);
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.before"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>before (n, func)](#apidoc.element.lodash-node.before)
- description and source-code
```javascript
function before(n, func) {
  var result;
  if (typeof func != 'function') {
    if (typeof n == 'function') {
      var temp = n;
      n = func;
      func = temp;
    } else {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
  }
  return function() {
    if (--n > 0) {
      result = func.apply(this, arguments);
    }
    if (n <= 1) {
      func = undefined;
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.bind"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>bind ()](#apidoc.element.lodash-node.bind)
- description and source-code
```javascript
bind = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.bindAll"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>bindAll ()](#apidoc.element.lodash-node.bindAll)
- description and source-code
```javascript
bindAll = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.bindKey"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>bindKey ()](#apidoc.element.lodash-node.bindKey)
- description and source-code
```javascript
bindKey = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.callback"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>callback (func, thisArg, guard)](#apidoc.element.lodash-node.callback)
- description and source-code
```javascript
function callback(func, thisArg, guard) {
  if (guard && isIterateeCall(func, thisArg, guard)) {
    thisArg = undefined;
  }
  return isObjectLike(func)
    ? matches(func)
    : baseCallback(func, thisArg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.camelCase"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>camelCase (string)](#apidoc.element.lodash-node.camelCase)
- description and source-code
```javascript
camelCase = function (string) {
  var index = -1,
      array = words(deburr(string)),
      length = array.length,
      result = '';

  while (++index < length) {
    result = callback(result, array[index], index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.capitalize"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>capitalize (string)](#apidoc.element.lodash-node.capitalize)
- description and source-code
```javascript
function capitalize(string) {
  string = baseToString(string);
  return string && (string.charAt(0).toUpperCase() + string.slice(1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.ceil"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>ceil (number, precision)](#apidoc.element.lodash-node.ceil)
- description and source-code
```javascript
ceil = function (number, precision) {
  precision = precision === undefined ? 0 : (+precision || 0);
  if (precision) {
    precision = pow(10, precision);
    return func(number * precision) / precision;
  }
  return func(number);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>chain (value)](#apidoc.element.lodash-node.chain)
- description and source-code
```javascript
function chain(value) {
  var result = lodash(value);
  result.__chain__ = true;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chunk"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>chunk (array, size, guard)](#apidoc.element.lodash-node.chunk)
- description and source-code
```javascript
function chunk(array, size, guard) {
  if (guard ? isIterateeCall(array, size, guard) : size == null) {
    size = 1;
  } else {
    size = nativeMax(nativeFloor(size) || 1, 1);
  }
  var index = 0,
      length = array ? array.length : 0,
      resIndex = -1,
      result = Array(nativeCeil(length / size));

  while (index < length) {
    result[++resIndex] = baseSlice(array, index, (index += size));
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.clone"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>clone (value, isDeep, customizer, thisArg)](#apidoc.element.lodash-node.clone)
- description and source-code
```javascript
function clone(value, isDeep, customizer, thisArg) {
  if (isDeep && typeof isDeep != 'boolean' && isIterateeCall(value, isDeep, customizer)) {
    isDeep = false;
  }
  else if (typeof isDeep == 'function') {
    thisArg = customizer;
    customizer = isDeep;
    isDeep = false;
  }
  return typeof customizer == 'function'
    ? baseClone(value, isDeep, bindCallback(customizer, thisArg, 3))
    : baseClone(value, isDeep);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.cloneDeep"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>cloneDeep (value, customizer, thisArg)](#apidoc.element.lodash-node.cloneDeep)
- description and source-code
```javascript
function cloneDeep(value, customizer, thisArg) {
  return typeof customizer == 'function'
    ? baseClone(value, true, bindCallback(customizer, thisArg, 3))
    : baseClone(value, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collect"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>collect (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collect)
- description and source-code
```javascript
function map(collection, iteratee, thisArg) {
  var func = isArray(collection) ? arrayMap : baseMap;
  iteratee = getCallback(iteratee, thisArg, 3);
  return func(collection, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.compact"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>compact (array)](#apidoc.element.lodash-node.compact)
- description and source-code
```javascript
function compact(array) {
  var index = -1,
      length = array ? array.length : 0,
      resIndex = -1,
      result = [];

  while (++index < length) {
    var value = array[index];
    if (value) {
      result[++resIndex] = value;
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.compose"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>compose ()](#apidoc.element.lodash-node.compose)
- description and source-code
```javascript
compose = function () {
  var wrapper,
      length = arguments.length,
      index = fromRight ? length : -1,
      leftIndex = 0,
      funcs = Array(length);

  while ((fromRight ? index-- : ++index < length)) {
    var func = funcs[leftIndex++] = arguments[index];
    if (typeof func != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    if (!wrapper && LodashWrapper.prototype.thru && getFuncName(func) == 'wrapper') {
      wrapper = new LodashWrapper([], true);
    }
  }
  index = wrapper ? -1 : length;
  while (++index < length) {
    func = funcs[index];

    var funcName = getFuncName(func),
        data = funcName == 'wrapper' ? getData(func) : undefined;

    if (data && isLaziable(data[0]) && data[1] == (ARY_FLAG | CURRY_FLAG | PARTIAL_FLAG | REARG_FLAG) && !data[4].length && data
[9] == 1) {
      wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
    } else {
      wrapper = (func.length == 1 && isLaziable(func)) ? wrapper[funcName]() : wrapper.thru(func);
    }
  }
  return function() {
    var args = arguments,
        value = args[0];

    if (wrapper && args.length == 1 && isArray(value) && value.length >= LARGE_ARRAY_SIZE) {
      return wrapper.plant(value).value();
    }
    var index = 0,
        result = length ? funcs[index].apply(this, args) : value;

    while (++index < length) {
      result = funcs[index].call(this, result);
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.constant"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>constant (value)](#apidoc.element.lodash-node.constant)
- description and source-code
```javascript
function constant(value) {
  return function() {
    return value;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.contains"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>contains (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.contains)
- description and source-code
```javascript
function includes(collection, target, fromIndex, guard) {
  var length = collection ? getLength(collection) : 0;
  if (!isLength(length)) {
    collection = values(collection);
    length = collection.length;
  }
  if (typeof fromIndex != 'number' || (guard && isIterateeCall(target, fromIndex, guard))) {
    fromIndex = 0;
  } else {
    fromIndex = fromIndex < 0 ? nativeMax(length + fromIndex, 0) : (fromIndex || 0);
  }
  return (typeof collection == 'string' || !isArray(collection) && isString(collection))
    ? (fromIndex <= length && collection.indexOf(target, fromIndex) > -1)
    : (!!length && getIndexOf(collection, target, fromIndex) > -1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.countBy"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>countBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.countBy)
- description and source-code
```javascript
countBy = function (collection, iteratee, thisArg) {
  var result = initializer ? initializer() : {};
  iteratee = getCallback(iteratee, thisArg, 3);

  if (isArray(collection)) {
    var index = -1,
        length = collection.length;

    while (++index < length) {
      var value = collection[index];
      setter(result, value, iteratee(value, index, collection), collection);
    }
  } else {
    baseEach(collection, function(value, key, collection) {
      setter(result, value, iteratee(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.create"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>create (prototype, properties, guard)](#apidoc.element.lodash-node.create)
- description and source-code
```javascript
function create(prototype, properties, guard) {
  var result = baseCreate(prototype);
  if (guard && isIterateeCall(prototype, properties, guard)) {
    properties = undefined;
  }
  return properties ? baseAssign(result, properties) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.curry"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>curry (func, arity, guard)](#apidoc.element.lodash-node.curry)
- description and source-code
```javascript
function curryFunc(func, arity, guard) {
  if (guard && isIterateeCall(func, arity, guard)) {
    arity = undefined;
  }
  var result = createWrapper(func, flag, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = curryFunc.placeholder;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.curryRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>curryRight (func, arity, guard)](#apidoc.element.lodash-node.curryRight)
- description and source-code
```javascript
function curryFunc(func, arity, guard) {
  if (guard && isIterateeCall(func, arity, guard)) {
    arity = undefined;
  }
  var result = createWrapper(func, flag, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = curryFunc.placeholder;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.debounce"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>debounce (func, wait, options)](#apidoc.element.lodash-node.debounce)
- description and source-code
```javascript
function debounce(func, wait, options) {
  var args,
      maxTimeoutId,
      result,
      stamp,
      thisArg,
      timeoutId,
      trailingCall,
      lastCalled = 0,
      maxWait = false,
      trailing = true;

  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  wait = wait < 0 ? 0 : (+wait || 0);
  if (options === true) {
    var leading = true;
    trailing = false;
  } else if (isObject(options)) {
    leading = !!options.leading;
    maxWait = 'maxWait' in options && nativeMax(+options.maxWait || 0, wait);
    trailing = 'trailing' in options ? !!options.trailing : trailing;
  }

  function cancel() {
    if (timeoutId) {
      clearTimeout(timeoutId);
    }
    if (maxTimeoutId) {
      clearTimeout(maxTimeoutId);
    }
    lastCalled = 0;
    maxTimeoutId = timeoutId = trailingCall = undefined;
  }

  function complete(isCalled, id) {
    if (id) {
      clearTimeout(id);
    }
    maxTimeoutId = timeoutId = trailingCall = undefined;
    if (isCalled) {
      lastCalled = now();
      result = func.apply(thisArg, args);
      if (!timeoutId && !maxTimeoutId) {
        args = thisArg = undefined;
      }
    }
  }

  function delayed() {
    var remaining = wait - (now() - stamp);
    if (remaining <= 0 || remaining > wait) {
      complete(trailingCall, maxTimeoutId);
    } else {
      timeoutId = setTimeout(delayed, remaining);
    }
  }

  function maxDelayed() {
    complete(trailing, timeoutId);
  }

  function debounced() {
    args = arguments;
    stamp = now();
    thisArg = this;
    trailingCall = trailing && (timeoutId || !leading);

    if (maxWait === false) {
      var leadingCall = leading && !timeoutId;
    } else {
      if (!maxTimeoutId && !leading) {
        lastCalled = stamp;
      }
      var remaining = maxWait - (stamp - lastCalled),
          isCalled = remaining <= 0 || remaining > maxWait;

      if (isCalled) {
        if (maxTimeoutId) {
          maxTimeoutId = clearTimeout(maxTimeoutId);
        }
        lastCalled = stamp;
        result = func.apply(thisArg, args);
      }
      else if (!maxTimeoutId) {
        maxTimeoutId = setTimeout(maxDelayed, remaining);
      }
    }
    if (isCalled && timeoutId) {
      timeoutId = clearTimeout(timeoutId);
    }
    else if (!timeoutId && wait !== maxWait) {
      timeoutId = setTimeout(delayed, wait);
    }
    if (leadingCall) {
      isCalled = true;
      result = func.apply(thisArg, args);
    }
    if (isCalled && !timeoutId && !maxTimeoutId) {
      args = thisArg = undefined;
    }
    return result;
  }
  debounced.cancel = cancel;
  return debounced;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.deburr"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>deburr (string)](#apidoc.element.lodash-node.deburr)
- description and source-code
```javascript
function deburr(string) {
  string = baseToString(string);
  return string && string.replace(reLatin1, deburrLetter).replace(reComboMark, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.defaults"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>defaults ()](#apidoc.element.lodash-node.defaults)
- description and source-code
```javascript
defaults = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.defaultsDeep"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>defaultsDeep ()](#apidoc.element.lodash-node.defaultsDeep)
- description and source-code
```javascript
defaultsDeep = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.defer"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>defer ()](#apidoc.element.lodash-node.defer)
- description and source-code
```javascript
defer = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.delay"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>delay ()](#apidoc.element.lodash-node.delay)
- description and source-code
```javascript
delay = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.detect"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>detect (collection, predicate, thisArg)](#apidoc.element.lodash-node.detect)
- description and source-code
```javascript
detect = function (collection, predicate, thisArg) {
  predicate = getCallback(predicate, thisArg, 3);
  if (isArray(collection)) {
    var index = baseFindIndex(collection, predicate, fromRight);
    return index > -1 ? collection[index] : undefined;
  }
  return baseFind(collection, predicate, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.difference"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>difference ()](#apidoc.element.lodash-node.difference)
- description and source-code
```javascript
difference = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.drop"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>drop (array, n, guard)](#apidoc.element.lodash-node.drop)
- description and source-code
```javascript
function drop(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (guard ? isIterateeCall(array, n, guard) : n == null) {
    n = 1;
  }
  return baseSlice(array, n < 0 ? 0 : n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.dropRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>dropRight (array, n, guard)](#apidoc.element.lodash-node.dropRight)
- description and source-code
```javascript
function dropRight(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (guard ? isIterateeCall(array, n, guard) : n == null) {
    n = 1;
  }
  n = length - (+n || 0);
  return baseSlice(array, 0, n < 0 ? 0 : n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.dropRightWhile"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>dropRightWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.dropRightWhile)
- description and source-code
```javascript
function dropRightWhile(array, predicate, thisArg) {
  return (array && array.length)
    ? baseWhile(array, getCallback(predicate, thisArg, 3), true, true)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.dropWhile"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>dropWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.dropWhile)
- description and source-code
```javascript
function dropWhile(array, predicate, thisArg) {
  return (array && array.length)
    ? baseWhile(array, getCallback(predicate, thisArg, 3), true)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.each"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>each (collection, iteratee, thisArg)](#apidoc.element.lodash-node.each)
- description and source-code
```javascript
each = function (collection, iteratee, thisArg) {
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee)
    : eachFunc(collection, bindCallback(iteratee, thisArg, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.eachRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>eachRight (collection, iteratee, thisArg)](#apidoc.element.lodash-node.eachRight)
- description and source-code
```javascript
eachRight = function (collection, iteratee, thisArg) {
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee)
    : eachFunc(collection, bindCallback(iteratee, thisArg, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.endsWith"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>endsWith (string, target, position)](#apidoc.element.lodash-node.endsWith)
- description and source-code
```javascript
function endsWith(string, target, position) {
  string = baseToString(string);
  target = (target + '');

  var length = string.length;
  position = position === undefined
    ? length
    : nativeMin(position < 0 ? 0 : (+position || 0), length);

  position -= target.length;
  return position >= 0 && string.indexOf(target, position) == position;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.eq"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>eq (value, other, customizer, thisArg)](#apidoc.element.lodash-node.eq)
- description and source-code
```javascript
function isEqual(value, other, customizer, thisArg) {
  customizer = typeof customizer == 'function' ? bindCallback(customizer, thisArg, 3) : undefined;
  var result = customizer ? customizer(value, other) : undefined;
  return  result === undefined ? baseIsEqual(value, other, customizer) : !!result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.escape"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>escape (string)](#apidoc.element.lodash-node.escape)
- description and source-code
```javascript
function escape(string) {
  // Reset 'lastIndex' because in IE < 9 'String#replace' does not.
  string = baseToString(string);
  return (string && reHasUnescapedHtml.test(string))
    ? string.replace(reUnescapedHtml, escapeHtmlChar)
    : string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.escapeRegExp"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>escapeRegExp (string)](#apidoc.element.lodash-node.escapeRegExp)
- description and source-code
```javascript
function escapeRegExp(string) {
  string = baseToString(string);
  return (string && reHasRegExpChars.test(string))
    ? string.replace(reRegExpChars, escapeRegExpChar)
    : (string || '(?:)');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.every"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>every (collection, predicate, thisArg)](#apidoc.element.lodash-node.every)
- description and source-code
```javascript
function every(collection, predicate, thisArg) {
  var func = isArray(collection) ? arrayEvery : baseEvery;
  if (thisArg && isIterateeCall(collection, predicate, thisArg)) {
    predicate = undefined;
  }
  if (typeof predicate != 'function' || thisArg !== undefined) {
    predicate = getCallback(predicate, thisArg, 3);
  }
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.extend"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>extend ()](#apidoc.element.lodash-node.extend)
- description and source-code
```javascript
extend = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.fill"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>fill (array, value, start, end)](#apidoc.element.lodash-node.fill)
- description and source-code
```javascript
function fill(array, value, start, end) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (start && typeof start != 'number' && isIterateeCall(array, value, start)) {
    start = 0;
    end = length;
  }
  return baseFill(array, value, start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.filter"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>filter (collection, predicate, thisArg)](#apidoc.element.lodash-node.filter)
- description and source-code
```javascript
function filter(collection, predicate, thisArg) {
  var func = isArray(collection) ? arrayFilter : baseFilter;
  predicate = getCallback(predicate, thisArg, 3);
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.find"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>find (collection, predicate, thisArg)](#apidoc.element.lodash-node.find)
- description and source-code
```javascript
find = function (collection, predicate, thisArg) {
  predicate = getCallback(predicate, thisArg, 3);
  if (isArray(collection)) {
    var index = baseFindIndex(collection, predicate, fromRight);
    return index > -1 ? collection[index] : undefined;
  }
  return baseFind(collection, predicate, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.findIndex"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>findIndex (array, predicate, thisArg)](#apidoc.element.lodash-node.findIndex)
- description and source-code
```javascript
findIndex = function (array, predicate, thisArg) {
  if (!(array && array.length)) {
    return -1;
  }
  predicate = getCallback(predicate, thisArg, 3);
  return baseFindIndex(array, predicate, fromRight);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.findKey"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>findKey (object, predicate, thisArg)](#apidoc.element.lodash-node.findKey)
- description and source-code
```javascript
findKey = function (object, predicate, thisArg) {
  predicate = getCallback(predicate, thisArg, 3);
  return baseFind(object, predicate, objectFunc, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.findLast"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>findLast (collection, predicate, thisArg)](#apidoc.element.lodash-node.findLast)
- description and source-code
```javascript
findLast = function (collection, predicate, thisArg) {
  predicate = getCallback(predicate, thisArg, 3);
  if (isArray(collection)) {
    var index = baseFindIndex(collection, predicate, fromRight);
    return index > -1 ? collection[index] : undefined;
  }
  return baseFind(collection, predicate, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.findLastIndex"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>findLastIndex (array, predicate, thisArg)](#apidoc.element.lodash-node.findLastIndex)
- description and source-code
```javascript
findLastIndex = function (array, predicate, thisArg) {
  if (!(array && array.length)) {
    return -1;
  }
  predicate = getCallback(predicate, thisArg, 3);
  return baseFindIndex(array, predicate, fromRight);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.findLastKey"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>findLastKey (object, predicate, thisArg)](#apidoc.element.lodash-node.findLastKey)
- description and source-code
```javascript
findLastKey = function (object, predicate, thisArg) {
  predicate = getCallback(predicate, thisArg, 3);
  return baseFind(object, predicate, objectFunc, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.findWhere"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>findWhere (collection, source)](#apidoc.element.lodash-node.findWhere)
- description and source-code
```javascript
function findWhere(collection, source) {
  return find(collection, baseMatches(source));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.first"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>first (array)](#apidoc.element.lodash-node.first)
- description and source-code
```javascript
function first(array) {
  return array ? array[0] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.flatten"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>flatten (array, isDeep, guard)](#apidoc.element.lodash-node.flatten)
- description and source-code
```javascript
function flatten(array, isDeep, guard) {
  var length = array ? array.length : 0;
  if (guard && isIterateeCall(array, isDeep, guard)) {
    isDeep = false;
  }
  return length ? baseFlatten(array, isDeep) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.flattenDeep"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>flattenDeep (array)](#apidoc.element.lodash-node.flattenDeep)
- description and source-code
```javascript
function flattenDeep(array) {
  var length = array ? array.length : 0;
  return length ? baseFlatten(array, true) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.floor"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>floor (number, precision)](#apidoc.element.lodash-node.floor)
- description and source-code
```javascript
floor = function (number, precision) {
  precision = precision === undefined ? 0 : (+precision || 0);
  if (precision) {
    precision = pow(10, precision);
    return func(number * precision) / precision;
  }
  return func(number);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.flow"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>flow ()](#apidoc.element.lodash-node.flow)
- description and source-code
```javascript
flow = function () {
  var wrapper,
      length = arguments.length,
      index = fromRight ? length : -1,
      leftIndex = 0,
      funcs = Array(length);

  while ((fromRight ? index-- : ++index < length)) {
    var func = funcs[leftIndex++] = arguments[index];
    if (typeof func != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    if (!wrapper && LodashWrapper.prototype.thru && getFuncName(func) == 'wrapper') {
      wrapper = new LodashWrapper([], true);
    }
  }
  index = wrapper ? -1 : length;
  while (++index < length) {
    func = funcs[index];

    var funcName = getFuncName(func),
        data = funcName == 'wrapper' ? getData(func) : undefined;

    if (data && isLaziable(data[0]) && data[1] == (ARY_FLAG | CURRY_FLAG | PARTIAL_FLAG | REARG_FLAG) && !data[4].length && data
[9] == 1) {
      wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
    } else {
      wrapper = (func.length == 1 && isLaziable(func)) ? wrapper[funcName]() : wrapper.thru(func);
    }
  }
  return function() {
    var args = arguments,
        value = args[0];

    if (wrapper && args.length == 1 && isArray(value) && value.length >= LARGE_ARRAY_SIZE) {
      return wrapper.plant(value).value();
    }
    var index = 0,
        result = length ? funcs[index].apply(this, args) : value;

    while (++index < length) {
      result = funcs[index].call(this, result);
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.flowRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>flowRight ()](#apidoc.element.lodash-node.flowRight)
- description and source-code
```javascript
flowRight = function () {
  var wrapper,
      length = arguments.length,
      index = fromRight ? length : -1,
      leftIndex = 0,
      funcs = Array(length);

  while ((fromRight ? index-- : ++index < length)) {
    var func = funcs[leftIndex++] = arguments[index];
    if (typeof func != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    if (!wrapper && LodashWrapper.prototype.thru && getFuncName(func) == 'wrapper') {
      wrapper = new LodashWrapper([], true);
    }
  }
  index = wrapper ? -1 : length;
  while (++index < length) {
    func = funcs[index];

    var funcName = getFuncName(func),
        data = funcName == 'wrapper' ? getData(func) : undefined;

    if (data && isLaziable(data[0]) && data[1] == (ARY_FLAG | CURRY_FLAG | PARTIAL_FLAG | REARG_FLAG) && !data[4].length && data
[9] == 1) {
      wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
    } else {
      wrapper = (func.length == 1 && isLaziable(func)) ? wrapper[funcName]() : wrapper.thru(func);
    }
  }
  return function() {
    var args = arguments,
        value = args[0];

    if (wrapper && args.length == 1 && isArray(value) && value.length >= LARGE_ARRAY_SIZE) {
      return wrapper.plant(value).value();
    }
    var index = 0,
        result = length ? funcs[index].apply(this, args) : value;

    while (++index < length) {
      result = funcs[index].call(this, result);
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.foldl"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>foldl (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.foldl)
- description and source-code
```javascript
foldl = function (collection, iteratee, accumulator, thisArg) {
  var initFromArray = arguments.length < 3;
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee, accumulator, initFromArray)
    : baseReduce(collection, getCallback(iteratee, thisArg, 4), accumulator, initFromArray, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.foldr"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>foldr (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.foldr)
- description and source-code
```javascript
foldr = function (collection, iteratee, accumulator, thisArg) {
  var initFromArray = arguments.length < 3;
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee, accumulator, initFromArray)
    : baseReduce(collection, getCallback(iteratee, thisArg, 4), accumulator, initFromArray, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.forEach"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>forEach (collection, iteratee, thisArg)](#apidoc.element.lodash-node.forEach)
- description and source-code
```javascript
forEach = function (collection, iteratee, thisArg) {
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee)
    : eachFunc(collection, bindCallback(iteratee, thisArg, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.forEachRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>forEachRight (collection, iteratee, thisArg)](#apidoc.element.lodash-node.forEachRight)
- description and source-code
```javascript
forEachRight = function (collection, iteratee, thisArg) {
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee)
    : eachFunc(collection, bindCallback(iteratee, thisArg, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.forIn"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>forIn (object, iteratee, thisArg)](#apidoc.element.lodash-node.forIn)
- description and source-code
```javascript
forIn = function (object, iteratee, thisArg) {
  if (typeof iteratee != 'function' || thisArg !== undefined) {
    iteratee = bindCallback(iteratee, thisArg, 3);
  }
  return objectFunc(object, iteratee, keysIn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.forInRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>forInRight (object, iteratee, thisArg)](#apidoc.element.lodash-node.forInRight)
- description and source-code
```javascript
forInRight = function (object, iteratee, thisArg) {
  if (typeof iteratee != 'function' || thisArg !== undefined) {
    iteratee = bindCallback(iteratee, thisArg, 3);
  }
  return objectFunc(object, iteratee, keysIn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.forOwn"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>forOwn (object, iteratee, thisArg)](#apidoc.element.lodash-node.forOwn)
- description and source-code
```javascript
forOwn = function (object, iteratee, thisArg) {
  if (typeof iteratee != 'function' || thisArg !== undefined) {
    iteratee = bindCallback(iteratee, thisArg, 3);
  }
  return objectFunc(object, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.forOwnRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>forOwnRight (object, iteratee, thisArg)](#apidoc.element.lodash-node.forOwnRight)
- description and source-code
```javascript
forOwnRight = function (object, iteratee, thisArg) {
  if (typeof iteratee != 'function' || thisArg !== undefined) {
    iteratee = bindCallback(iteratee, thisArg, 3);
  }
  return objectFunc(object, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.functions"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>functions (object)](#apidoc.element.lodash-node.functions)
- description and source-code
```javascript
function functions(object) {
  return baseFunctions(object, keysIn(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.get"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>get (object, path, defaultValue)](#apidoc.element.lodash-node.get)
- description and source-code
```javascript
function get(object, path, defaultValue) {
  var result = object == null ? undefined : baseGet(object, toPath(path), (path + ''));
  return result === undefined ? defaultValue : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.groupBy"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>groupBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.groupBy)
- description and source-code
```javascript
groupBy = function (collection, iteratee, thisArg) {
  var result = initializer ? initializer() : {};
  iteratee = getCallback(iteratee, thisArg, 3);

  if (isArray(collection)) {
    var index = -1,
        length = collection.length;

    while (++index < length) {
      var value = collection[index];
      setter(result, value, iteratee(value, index, collection), collection);
    }
  } else {
    baseEach(collection, function(value, key, collection) {
      setter(result, value, iteratee(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.gt"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>gt (value, other)](#apidoc.element.lodash-node.gt)
- description and source-code
```javascript
function gt(value, other) {
  return value > other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.gte"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>gte (value, other)](#apidoc.element.lodash-node.gte)
- description and source-code
```javascript
function gte(value, other) {
  return value >= other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.has"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>has (object, path)](#apidoc.element.lodash-node.has)
- description and source-code
```javascript
function has(object, path) {
  if (object == null) {
    return false;
  }
  var result = hasOwnProperty.call(object, path);
  if (!result && !isKey(path)) {
    path = toPath(path);
    object = path.length == 1 ? object : baseGet(object, baseSlice(path, 0, -1));
    if (object == null) {
      return false;
    }
    path = last(path);
    result = hasOwnProperty.call(object, path);
  }
  return result || (isLength(object.length) && isIndex(path, object.length) &&
    (isArray(object) || isArguments(object)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.head"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>head (array)](#apidoc.element.lodash-node.head)
- description and source-code
```javascript
function first(array) {
  return array ? array[0] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.identity"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>identity (value)](#apidoc.element.lodash-node.identity)
- description and source-code
```javascript
function identity(value) {
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.inRange"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>inRange (value, start, end)](#apidoc.element.lodash-node.inRange)
- description and source-code
```javascript
function inRange(value, start, end) {
  start = +start || 0;
  if (end === undefined) {
    end = start;
    start = 0;
  } else {
    end = +end || 0;
  }
  return value >= nativeMin(start, end) && value < nativeMax(start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.include"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>include (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.include)
- description and source-code
```javascript
function includes(collection, target, fromIndex, guard) {
  var length = collection ? getLength(collection) : 0;
  if (!isLength(length)) {
    collection = values(collection);
    length = collection.length;
  }
  if (typeof fromIndex != 'number' || (guard && isIterateeCall(target, fromIndex, guard))) {
    fromIndex = 0;
  } else {
    fromIndex = fromIndex < 0 ? nativeMax(length + fromIndex, 0) : (fromIndex || 0);
  }
  return (typeof collection == 'string' || !isArray(collection) && isString(collection))
    ? (fromIndex <= length && collection.indexOf(target, fromIndex) > -1)
    : (!!length && getIndexOf(collection, target, fromIndex) > -1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.includes"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>includes (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.includes)
- description and source-code
```javascript
function includes(collection, target, fromIndex, guard) {
  var length = collection ? getLength(collection) : 0;
  if (!isLength(length)) {
    collection = values(collection);
    length = collection.length;
  }
  if (typeof fromIndex != 'number' || (guard && isIterateeCall(target, fromIndex, guard))) {
    fromIndex = 0;
  } else {
    fromIndex = fromIndex < 0 ? nativeMax(length + fromIndex, 0) : (fromIndex || 0);
  }
  return (typeof collection == 'string' || !isArray(collection) && isString(collection))
    ? (fromIndex <= length && collection.indexOf(target, fromIndex) > -1)
    : (!!length && getIndexOf(collection, target, fromIndex) > -1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.indexBy"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>indexBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.indexBy)
- description and source-code
```javascript
indexBy = function (collection, iteratee, thisArg) {
  var result = initializer ? initializer() : {};
  iteratee = getCallback(iteratee, thisArg, 3);

  if (isArray(collection)) {
    var index = -1,
        length = collection.length;

    while (++index < length) {
      var value = collection[index];
      setter(result, value, iteratee(value, index, collection), collection);
    }
  } else {
    baseEach(collection, function(value, key, collection) {
      setter(result, value, iteratee(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.indexOf"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>indexOf (array, value, fromIndex)](#apidoc.element.lodash-node.indexOf)
- description and source-code
```javascript
function indexOf(array, value, fromIndex) {
  var length = array ? array.length : 0;
  if (!length) {
    return -1;
  }
  if (typeof fromIndex == 'number') {
    fromIndex = fromIndex < 0 ? nativeMax(length + fromIndex, 0) : fromIndex;
  } else if (fromIndex) {
    var index = binaryIndex(array, value);
    if (index < length &&
        (value === value ? (value === array[index]) : (array[index] !== array[index]))) {
      return index;
    }
    return -1;
  }
  return baseIndexOf(array, value, fromIndex || 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.initial"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>initial (array)](#apidoc.element.lodash-node.initial)
- description and source-code
```javascript
function initial(array) {
  return dropRight(array, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.inject"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>inject (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.inject)
- description and source-code
```javascript
inject = function (collection, iteratee, accumulator, thisArg) {
  var initFromArray = arguments.length < 3;
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee, accumulator, initFromArray)
    : baseReduce(collection, getCallback(iteratee, thisArg, 4), accumulator, initFromArray, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.intersection"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>intersection ()](#apidoc.element.lodash-node.intersection)
- description and source-code
```javascript
intersection = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.invert"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>invert (object, multiValue, guard)](#apidoc.element.lodash-node.invert)
- description and source-code
```javascript
function invert(object, multiValue, guard) {
  if (guard && isIterateeCall(object, multiValue, guard)) {
    multiValue = undefined;
  }
  var index = -1,
      props = keys(object),
      length = props.length,
      result = {};

  while (++index < length) {
    var key = props[index],
        value = object[key];

    if (multiValue) {
      if (hasOwnProperty.call(result, value)) {
        result[value].push(key);
      } else {
        result[value] = [key];
      }
    }
    else {
      result[value] = key;
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.invoke"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>invoke ()](#apidoc.element.lodash-node.invoke)
- description and source-code
```javascript
invoke = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isArguments"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isArguments (value)](#apidoc.element.lodash-node.isArguments)
- description and source-code
```javascript
function isArguments(value) {
  return isObjectLike(value) && isArrayLike(value) &&
    hasOwnProperty.call(value, 'callee') && !propertyIsEnumerable.call(value, 'callee');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isArray"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isArray ()](#apidoc.element.lodash-node.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isBoolean"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isBoolean (value)](#apidoc.element.lodash-node.isBoolean)
- description and source-code
```javascript
function isBoolean(value) {
  return value === true || value === false || (isObjectLike(value) && objToString.call(value) == boolTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isDate"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isDate (value)](#apidoc.element.lodash-node.isDate)
- description and source-code
```javascript
function isDate(value) {
  return isObjectLike(value) && objToString.call(value) == dateTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isElement"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isElement (value)](#apidoc.element.lodash-node.isElement)
- description and source-code
```javascript
function isElement(value) {
  return !!value && value.nodeType === 1 && isObjectLike(value) && !isPlainObject(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isEmpty"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isEmpty (value)](#apidoc.element.lodash-node.isEmpty)
- description and source-code
```javascript
function isEmpty(value) {
  if (value == null) {
    return true;
  }
  if (isArrayLike(value) && (isArray(value) || isString(value) || isArguments(value) ||
      (isObjectLike(value) && isFunction(value.splice)))) {
    return !value.length;
  }
  return !keys(value).length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isEqual"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isEqual (value, other, customizer, thisArg)](#apidoc.element.lodash-node.isEqual)
- description and source-code
```javascript
function isEqual(value, other, customizer, thisArg) {
  customizer = typeof customizer == 'function' ? bindCallback(customizer, thisArg, 3) : undefined;
  var result = customizer ? customizer(value, other) : undefined;
  return  result === undefined ? baseIsEqual(value, other, customizer) : !!result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isError"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isError (value)](#apidoc.element.lodash-node.isError)
- description and source-code
```javascript
function isError(value) {
  return isObjectLike(value) && typeof value.message == 'string' && objToString.call(value) == errorTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isFinite"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isFinite (value)](#apidoc.element.lodash-node.isFinite)
- description and source-code
```javascript
function isFinite(value) {
  return typeof value == 'number' && nativeIsFinite(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isFunction"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isFunction (value)](#apidoc.element.lodash-node.isFunction)
- description and source-code
```javascript
function isFunction(value) {
  // The use of 'Object#toString' avoids issues with the 'typeof' operator
  // in older versions of Chrome and Safari which return 'function' for regexes
  // and Safari 8 which returns 'object' for typed array constructors.
  return isObject(value) && objToString.call(value) == funcTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isMatch"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isMatch (object, source, customizer, thisArg)](#apidoc.element.lodash-node.isMatch)
- description and source-code
```javascript
function isMatch(object, source, customizer, thisArg) {
  customizer = typeof customizer == 'function' ? bindCallback(customizer, thisArg, 3) : undefined;
  return baseIsMatch(object, getMatchData(source), customizer);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isNaN"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isNaN (value)](#apidoc.element.lodash-node.isNaN)
- description and source-code
```javascript
function isNaN(value) {
  // An 'NaN' primitive is the only value that is not equal to itself.
  // Perform the 'toStringTag' check first to avoid errors with some host objects in IE.
  return isNumber(value) && value != +value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isNative"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isNative (value)](#apidoc.element.lodash-node.isNative)
- description and source-code
```javascript
function isNative(value) {
  if (value == null) {
    return false;
  }
  if (isFunction(value)) {
    return reIsNative.test(fnToString.call(value));
  }
  return isObjectLike(value) && reIsHostCtor.test(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isNull"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isNull (value)](#apidoc.element.lodash-node.isNull)
- description and source-code
```javascript
function isNull(value) {
  return value === null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isNumber"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isNumber (value)](#apidoc.element.lodash-node.isNumber)
- description and source-code
```javascript
function isNumber(value) {
  return typeof value == 'number' || (isObjectLike(value) && objToString.call(value) == numberTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isObject"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isObject (value)](#apidoc.element.lodash-node.isObject)
- description and source-code
```javascript
function isObject(value) {
  // Avoid a V8 JIT bug in Chrome 19-20.
  // See https://code.google.com/p/v8/issues/detail?id=2291 for more details.
  var type = typeof value;
  return !!value && (type == 'object' || type == 'function');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isPlainObject"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isPlainObject (value)](#apidoc.element.lodash-node.isPlainObject)
- description and source-code
```javascript
function isPlainObject(value) {
  var Ctor;

  // Exit early for non 'Object' objects.
  if (!(isObjectLike(value) && objToString.call(value) == objectTag && !isArguments(value)) ||
      (!hasOwnProperty.call(value, 'constructor') && (Ctor = value.constructor, typeof Ctor == 'function' && !(Ctor instanceof Ctor
)))) {
    return false;
  }
  // IE < 9 iterates inherited properties before own properties. If the first
  // iterated property is an object's own property then there are no inherited
  // enumerable properties.
  var result;
  // In most environments an object's own properties are iterated before
  // its inherited properties. If the last iterated property is an object's
  // own property then there are no inherited enumerable properties.
  baseForIn(value, function(subValue, key) {
    result = key;
  });
  return result === undefined || hasOwnProperty.call(value, result);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isRegExp"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isRegExp (value)](#apidoc.element.lodash-node.isRegExp)
- description and source-code
```javascript
function isRegExp(value) {
  return isObject(value) && objToString.call(value) == regexpTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isString"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isString (value)](#apidoc.element.lodash-node.isString)
- description and source-code
```javascript
function isString(value) {
  return typeof value == 'string' || (isObjectLike(value) && objToString.call(value) == stringTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isTypedArray"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isTypedArray (value)](#apidoc.element.lodash-node.isTypedArray)
- description and source-code
```javascript
function isTypedArray(value) {
  return isObjectLike(value) && isLength(value.length) && !!typedArrayTags[objToString.call(value)];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.isUndefined"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>isUndefined (value)](#apidoc.element.lodash-node.isUndefined)
- description and source-code
```javascript
function isUndefined(value) {
  return value === undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.iteratee"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>iteratee (func, thisArg, guard)](#apidoc.element.lodash-node.iteratee)
- description and source-code
```javascript
function callback(func, thisArg, guard) {
  if (guard && isIterateeCall(func, thisArg, guard)) {
    thisArg = undefined;
  }
  return isObjectLike(func)
    ? matches(func)
    : baseCallback(func, thisArg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.kebabCase"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>kebabCase (string)](#apidoc.element.lodash-node.kebabCase)
- description and source-code
```javascript
kebabCase = function (string) {
  var index = -1,
      array = words(deburr(string)),
      length = array.length,
      result = '';

  while (++index < length) {
    result = callback(result, array[index], index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.keys"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>keys (object)](#apidoc.element.lodash-node.keys)
- description and source-code
```javascript
keys = function (object) {
  var Ctor = object == null ? undefined : object.constructor;
  if ((typeof Ctor == 'function' && Ctor.prototype === object) ||
      (typeof object != 'function' && isArrayLike(object))) {
    return shimKeys(object);
  }
  return isObject(object) ? nativeKeys(object) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.keysIn"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>keysIn (object)](#apidoc.element.lodash-node.keysIn)
- description and source-code
```javascript
function keysIn(object) {
  if (object == null) {
    return [];
  }
  if (!isObject(object)) {
    object = Object(object);
  }
  var length = object.length;
  length = (length && isLength(length) &&
    (isArray(object) || isArguments(object)) && length) || 0;

  var Ctor = object.constructor,
      index = -1,
      isProto = typeof Ctor == 'function' && Ctor.prototype === object,
      result = Array(length),
      skipIndexes = length > 0;

  while (++index < length) {
    result[index] = (index + '');
  }
  for (var key in object) {
    if (!(skipIndexes && isIndex(key, length)) &&
        !(key == 'constructor' && (isProto || !hasOwnProperty.call(object, key)))) {
      result.push(key);
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.last"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>last (array)](#apidoc.element.lodash-node.last)
- description and source-code
```javascript
function last(array) {
  var length = array ? array.length : 0;
  return length ? array[length - 1] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lastIndexOf"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>lastIndexOf (array, value, fromIndex)](#apidoc.element.lodash-node.lastIndexOf)
- description and source-code
```javascript
function lastIndexOf(array, value, fromIndex) {
  var length = array ? array.length : 0;
  if (!length) {
    return -1;
  }
  var index = length;
  if (typeof fromIndex == 'number') {
    index = (fromIndex < 0 ? nativeMax(length + fromIndex, 0) : nativeMin(fromIndex || 0, length - 1)) + 1;
  } else if (fromIndex) {
    index = binaryIndex(array, value, true) - 1;
    var other = array[index];
    if (value === value ? (value === other) : (other !== other)) {
      return index;
    }
    return -1;
  }
  if (value !== value) {
    return indexOfNaN(array, index, true);
  }
  while (index--) {
    if (array[index] === value) {
      return index;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lt"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>lt (value, other)](#apidoc.element.lodash-node.lt)
- description and source-code
```javascript
function lt(value, other) {
  return value < other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lte"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>lte (value, other)](#apidoc.element.lodash-node.lte)
- description and source-code
```javascript
function lte(value, other) {
  return value <= other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.map"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>map (collection, iteratee, thisArg)](#apidoc.element.lodash-node.map)
- description and source-code
```javascript
function map(collection, iteratee, thisArg) {
  var func = isArray(collection) ? arrayMap : baseMap;
  iteratee = getCallback(iteratee, thisArg, 3);
  return func(collection, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.mapKeys"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>mapKeys (object, iteratee, thisArg)](#apidoc.element.lodash-node.mapKeys)
- description and source-code
```javascript
mapKeys = function (object, iteratee, thisArg) {
  var result = {};
  iteratee = getCallback(iteratee, thisArg, 3);

  baseForOwn(object, function(value, key, object) {
    var mapped = iteratee(value, key, object);
    key = isMapKeys ? mapped : key;
    value = isMapKeys ? value : mapped;
    result[key] = value;
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.mapValues"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>mapValues (object, iteratee, thisArg)](#apidoc.element.lodash-node.mapValues)
- description and source-code
```javascript
mapValues = function (object, iteratee, thisArg) {
  var result = {};
  iteratee = getCallback(iteratee, thisArg, 3);

  baseForOwn(object, function(value, key, object) {
    var mapped = iteratee(value, key, object);
    key = isMapKeys ? mapped : key;
    value = isMapKeys ? value : mapped;
    result[key] = value;
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.matches"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>matches (source)](#apidoc.element.lodash-node.matches)
- description and source-code
```javascript
function matches(source) {
  return baseMatches(baseClone(source, true));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.matchesProperty"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>matchesProperty (path, srcValue)](#apidoc.element.lodash-node.matchesProperty)
- description and source-code
```javascript
function matchesProperty(path, srcValue) {
  return baseMatchesProperty(path, baseClone(srcValue, true));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.max"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>max (collection, iteratee, thisArg)](#apidoc.element.lodash-node.max)
- description and source-code
```javascript
max = function (collection, iteratee, thisArg) {
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  iteratee = getCallback(iteratee, thisArg, 3);
  if (iteratee.length == 1) {
    collection = isArray(collection) ? collection : toIterable(collection);
    var result = arrayExtremum(collection, iteratee, comparator, exValue);
    if (!(collection.length && result === exValue)) {
      return result;
    }
  }
  return baseExtremum(collection, iteratee, comparator, exValue);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.memoize"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>memoize (func, resolver)](#apidoc.element.lodash-node.memoize)
- description and source-code
```javascript
function memoize(func, resolver) {
  if (typeof func != 'function' || (resolver && typeof resolver != 'function')) {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  var memoized = function() {
    var args = arguments,
        key = resolver ? resolver.apply(this, args) : args[0],
        cache = memoized.cache;

    if (cache.has(key)) {
      return cache.get(key);
    }
    var result = func.apply(this, args);
    memoized.cache = cache.set(key, result);
    return result;
  };
  memoized.cache = new memoize.Cache;
  return memoized;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.memoize.Cache"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>memoize.Cache ()](#apidoc.element.lodash-node.memoize.Cache)
- description and source-code
```javascript
function MapCache() {
  this.__data__ = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.merge"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>merge ()](#apidoc.element.lodash-node.merge)
- description and source-code
```javascript
merge = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.method"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>method ()](#apidoc.element.lodash-node.method)
- description and source-code
```javascript
method = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.methodOf"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>methodOf ()](#apidoc.element.lodash-node.methodOf)
- description and source-code
```javascript
methodOf = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.methods"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>methods (object)](#apidoc.element.lodash-node.methods)
- description and source-code
```javascript
function functions(object) {
  return baseFunctions(object, keysIn(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.min"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>min (collection, iteratee, thisArg)](#apidoc.element.lodash-node.min)
- description and source-code
```javascript
min = function (collection, iteratee, thisArg) {
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  iteratee = getCallback(iteratee, thisArg, 3);
  if (iteratee.length == 1) {
    collection = isArray(collection) ? collection : toIterable(collection);
    var result = arrayExtremum(collection, iteratee, comparator, exValue);
    if (!(collection.length && result === exValue)) {
      return result;
    }
  }
  return baseExtremum(collection, iteratee, comparator, exValue);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.mixin"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>mixin (object, source, options)](#apidoc.element.lodash-node.mixin)
- description and source-code
```javascript
function mixin(object, source, options) {
  if (options == null) {
    var isObj = isObject(source),
        props = isObj ? keys(source) : undefined,
        methodNames = (props && props.length) ? baseFunctions(source, props) : undefined;

    if (!(methodNames ? methodNames.length : isObj)) {
      methodNames = false;
      options = source;
      source = object;
      object = this;
    }
  }
  if (!methodNames) {
    methodNames = baseFunctions(source, keys(source));
  }
  var chain = true,
      index = -1,
      isFunc = isFunction(object),
      length = methodNames.length;

  if (options === false) {
    chain = false;
  } else if (isObject(options) && 'chain' in options) {
    chain = options.chain;
  }
  while (++index < length) {
    var methodName = methodNames[index],
        func = source[methodName];

    object[methodName] = func;
    if (isFunc) {
      object.prototype[methodName] = (function(func) {
        return function() {
          var chainAll = this.__chain__;
          if (chain || chainAll) {
            var result = object(this.__wrapped__),
                actions = result.__actions__ = arrayCopy(this.__actions__);

            actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
            result.__chain__ = chainAll;
            return result;
          }
          return func.apply(object, arrayPush([this.value()], arguments));
        };
      }(func));
    }
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.modArgs"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>modArgs ()](#apidoc.element.lodash-node.modArgs)
- description and source-code
```javascript
modArgs = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.negate"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>negate (predicate)](#apidoc.element.lodash-node.negate)
- description and source-code
```javascript
function negate(predicate) {
  if (typeof predicate != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  return function() {
    return !predicate.apply(this, arguments);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.noConflict"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>noConflict ()](#apidoc.element.lodash-node.noConflict)
- description and source-code
```javascript
function noConflict() {
  root._ = oldDash;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.noop"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>noop ()](#apidoc.element.lodash-node.noop)
- description and source-code
```javascript
function noop() {
  // No operation performed.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.now"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>now ()](#apidoc.element.lodash-node.now)
- description and source-code
```javascript
function now() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>object (props, values)](#apidoc.element.lodash-node.object)
- description and source-code
```javascript
function zipObject(props, values) {
  var index = -1,
      length = props ? props.length : 0,
      result = {};

  if (length && !values && !isArray(props[0])) {
    values = [];
  }
  while (++index < length) {
    var key = props[index];
    if (values) {
      result[key] = values[index];
    } else if (key) {
      result[key[0]] = key[1];
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.omit"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>omit ()](#apidoc.element.lodash-node.omit)
- description and source-code
```javascript
omit = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.once"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>once (func)](#apidoc.element.lodash-node.once)
- description and source-code
```javascript
function once(func) {
  return before(2, func);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.pad"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>pad (string, length, chars)](#apidoc.element.lodash-node.pad)
- description and source-code
```javascript
function pad(string, length, chars) {
  string = baseToString(string);
  length = +length;

  var strLength = string.length;
  if (strLength >= length || !nativeIsFinite(length)) {
    return string;
  }
  var mid = (length - strLength) / 2,
      leftLength = nativeFloor(mid),
      rightLength = nativeCeil(mid);

  chars = createPadding('', rightLength, chars);
  return chars.slice(0, leftLength) + string + chars;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.padLeft"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>padLeft (string, length, chars)](#apidoc.element.lodash-node.padLeft)
- description and source-code
```javascript
padLeft = function (string, length, chars) {
  string = baseToString(string);
  return (fromRight ? string : '') + createPadding(string, length, chars) + (fromRight ? '' : string);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.padRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>padRight (string, length, chars)](#apidoc.element.lodash-node.padRight)
- description and source-code
```javascript
padRight = function (string, length, chars) {
  string = baseToString(string);
  return (fromRight ? string : '') + createPadding(string, length, chars) + (fromRight ? '' : string);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.pairs"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>pairs (object)](#apidoc.element.lodash-node.pairs)
- description and source-code
```javascript
function pairs(object) {
  object = toObject(object);

  var index = -1,
      props = keys(object),
      length = props.length,
      result = Array(length);

  while (++index < length) {
    var key = props[index];
    result[index] = [key, object[key]];
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.parseInt"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>parseInt (string, radix, guard)](#apidoc.element.lodash-node.parseInt)
- description and source-code
```javascript
function parseInt(string, radix, guard) {
  // Firefox < 21 and Opera < 15 follow ES3 for 'parseInt'.
  // Chrome fails to trim leading <BOM> whitespace characters.
  // See https://code.google.com/p/v8/issues/detail?id=3109 for more details.
  if (guard ? isIterateeCall(string, radix, guard) : radix == null) {
    radix = 0;
  } else if (radix) {
    radix = +radix;
  }
  string = trim(string);
  return nativeParseInt(string, radix || (reHasHexPrefix.test(string) ? 16 : 10));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.partial"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>partial ()](#apidoc.element.lodash-node.partial)
- description and source-code
```javascript
partial = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.partialRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>partialRight ()](#apidoc.element.lodash-node.partialRight)
- description and source-code
```javascript
partialRight = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.partition"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>partition (collection, iteratee, thisArg)](#apidoc.element.lodash-node.partition)
- description and source-code
```javascript
partition = function (collection, iteratee, thisArg) {
  var result = initializer ? initializer() : {};
  iteratee = getCallback(iteratee, thisArg, 3);

  if (isArray(collection)) {
    var index = -1,
        length = collection.length;

    while (++index < length) {
      var value = collection[index];
      setter(result, value, iteratee(value, index, collection), collection);
    }
  } else {
    baseEach(collection, function(value, key, collection) {
      setter(result, value, iteratee(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.pick"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>pick ()](#apidoc.element.lodash-node.pick)
- description and source-code
```javascript
pick = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.pluck"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>pluck (collection, path)](#apidoc.element.lodash-node.pluck)
- description and source-code
```javascript
function pluck(collection, path) {
  return map(collection, property(path));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.property"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>property (path)](#apidoc.element.lodash-node.property)
- description and source-code
```javascript
function property(path) {
  return isKey(path) ? baseProperty(path) : basePropertyDeep(path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.propertyOf"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>propertyOf (object)](#apidoc.element.lodash-node.propertyOf)
- description and source-code
```javascript
function propertyOf(object) {
  return function(path) {
    return baseGet(object, toPath(path), (path + ''));
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.pull"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>pull ()](#apidoc.element.lodash-node.pull)
- description and source-code
```javascript
function pull() {
  var args = arguments,
      array = args[0];

  if (!(array && array.length)) {
    return array;
  }
  var index = 0,
      indexOf = getIndexOf(),
      length = args.length;

  while (++index < length) {
    var fromIndex = 0,
        value = args[index];

    while ((fromIndex = indexOf(array, value, fromIndex)) > -1) {
      splice.call(array, fromIndex, 1);
    }
  }
  return array;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.pullAt"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>pullAt ()](#apidoc.element.lodash-node.pullAt)
- description and source-code
```javascript
pullAt = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.random"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>random (min, max, floating)](#apidoc.element.lodash-node.random)
- description and source-code
```javascript
function random(min, max, floating) {
  if (floating && isIterateeCall(min, max, floating)) {
    max = floating = undefined;
  }
  var noMin = min == null,
      noMax = max == null;

  if (floating == null) {
    if (noMax && typeof min == 'boolean') {
      floating = min;
      min = 1;
    }
    else if (typeof max == 'boolean') {
      floating = max;
      noMax = true;
    }
  }
  if (noMin && noMax) {
    max = 1;
    noMax = false;
  }
  min = +min || 0;
  if (noMax) {
    max = min;
    min = 0;
  } else {
    max = +max || 0;
  }
  if (floating || min % 1 || max % 1) {
    var rand = nativeRandom();
    return nativeMin(min + (rand * (max - min + parseFloat('1e-' + ((rand + '').length - 1)))), max);
  }
  return baseRandom(min, max);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.range"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>range (start, end, step)](#apidoc.element.lodash-node.range)
- description and source-code
```javascript
function range(start, end, step) {
  if (step && isIterateeCall(start, end, step)) {
    end = step = undefined;
  }
  start = +start || 0;
  step = step == null ? 1 : (+step || 0);

  if (end == null) {
    end = start;
    start = 0;
  } else {
    end = +end || 0;
  }
  // Use 'Array(length)' so engines like Chakra and V8 avoid slower modes.
  // See https://youtu.be/XAqIpGU8ZZk#t=17m25s for more details.
  var index = -1,
      length = nativeMax(nativeCeil((end - start) / (step || 1)), 0),
      result = Array(length);

  while (++index < length) {
    result[index] = start;
    start += step;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.rearg"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>rearg ()](#apidoc.element.lodash-node.rearg)
- description and source-code
```javascript
rearg = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.reduce"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>reduce (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.reduce)
- description and source-code
```javascript
reduce = function (collection, iteratee, accumulator, thisArg) {
  var initFromArray = arguments.length < 3;
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee, accumulator, initFromArray)
    : baseReduce(collection, getCallback(iteratee, thisArg, 4), accumulator, initFromArray, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.reduceRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>reduceRight (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.reduceRight)
- description and source-code
```javascript
reduceRight = function (collection, iteratee, accumulator, thisArg) {
  var initFromArray = arguments.length < 3;
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee, accumulator, initFromArray)
    : baseReduce(collection, getCallback(iteratee, thisArg, 4), accumulator, initFromArray, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.reject"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>reject (collection, predicate, thisArg)](#apidoc.element.lodash-node.reject)
- description and source-code
```javascript
function reject(collection, predicate, thisArg) {
  var func = isArray(collection) ? arrayFilter : baseFilter;
  predicate = getCallback(predicate, thisArg, 3);
  return func(collection, function(value, index, collection) {
    return !predicate(value, index, collection);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.remove"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>remove (array, predicate, thisArg)](#apidoc.element.lodash-node.remove)
- description and source-code
```javascript
function remove(array, predicate, thisArg) {
  var result = [];
  if (!(array && array.length)) {
    return result;
  }
  var index = -1,
      indexes = [],
      length = array.length;

  predicate = getCallback(predicate, thisArg, 3);
  while (++index < length) {
    var value = array[index];
    if (predicate(value, index, array)) {
      result.push(value);
      indexes.push(index);
    }
  }
  basePullAt(array, indexes);
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.repeat"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>repeat (string, n)](#apidoc.element.lodash-node.repeat)
- description and source-code
```javascript
function repeat(string, n) {
  var result = '';
  string = baseToString(string);
  n = +n;
  if (n < 1 || !string || !nativeIsFinite(n)) {
    return result;
  }
  // Leverage the exponentiation by squaring algorithm for a faster repeat.
  // See https://en.wikipedia.org/wiki/Exponentiation_by_squaring for more details.
  do {
    if (n % 2) {
      result += string;
    }
    n = nativeFloor(n / 2);
    string += string;
  } while (n);

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.rest"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>rest (array)](#apidoc.element.lodash-node.rest)
- description and source-code
```javascript
function rest(array) {
  return drop(array, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.restParam"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>restParam (func, start)](#apidoc.element.lodash-node.restParam)
- description and source-code
```javascript
function restParam(func, start) {
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  start = nativeMax(start === undefined ? (func.length - 1) : (+start || 0), 0);
  return function() {
    var args = arguments,
        index = -1,
        length = nativeMax(args.length - start, 0),
        rest = Array(length);

    while (++index < length) {
      rest[index] = args[start + index];
    }
    switch (start) {
      case 0: return func.call(this, rest);
      case 1: return func.call(this, args[0], rest);
      case 2: return func.call(this, args[0], args[1], rest);
    }
    var otherArgs = Array(start + 1);
    index = -1;
    while (++index < start) {
      otherArgs[index] = args[index];
    }
    otherArgs[start] = rest;
    return func.apply(this, otherArgs);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.result"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>result (object, path, defaultValue)](#apidoc.element.lodash-node.result)
- description and source-code
```javascript
function result(object, path, defaultValue) {
  var result = object == null ? undefined : object[path];
  if (result === undefined) {
    if (object != null && !isKey(path, object)) {
      path = toPath(path);
      object = path.length == 1 ? object : baseGet(object, baseSlice(path, 0, -1));
      result = object == null ? undefined : object[last(path)];
    }
    result = result === undefined ? defaultValue : result;
  }
  return isFunction(result) ? result.call(object) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.round"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>round (number, precision)](#apidoc.element.lodash-node.round)
- description and source-code
```javascript
round = function (number, precision) {
  precision = precision === undefined ? 0 : (+precision || 0);
  if (precision) {
    precision = pow(10, precision);
    return func(number * precision) / precision;
  }
  return func(number);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.runInContext"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>runInContext (context)](#apidoc.element.lodash-node.runInContext)
- description and source-code
```javascript
function runInContext(context) {
  // Avoid issues with some ES3 environments that attempt to use values, named
  // after built-in constructors like 'Object', for the creation of literals.
  // ES5 clears this up by stating that literals must use built-in constructors.
  // See https://es5.github.io/#x11.1.5 for more details.
  context = context ? _.defaults(root.Object(), context, _.pick(root, contextProps)) : root;

<span class="apidocCodeCommentSpan">  /** Native constructor references. */
</span>  var Array = context.Array,
      Date = context.Date,
      Error = context.Error,
      Function = context.Function,
      Math = context.Math,
      Number = context.Number,
      Object = context.Object,
      RegExp = context.RegExp,
      String = context.String,
      TypeError = context.TypeError;

  /** Used for native method references. */
  var arrayProto = Array.prototype,
      objectProto = Object.prototype,
      stringProto = String.prototype;

  /** Used to resolve the decompiled source of functions. */
  var fnToString = Function.prototype.toString;

  /** Used to check objects for own properties. */
  var hasOwnProperty = objectProto.hasOwnProperty;

  /** Used to generate unique IDs. */
  var idCounter = 0;

  /**
   * Used to resolve the ['toStringTag'](http://ecma-international.org/ecma-262/6.0/#sec-object.prototype.tostring)
   * of values.
   */
  var objToString = objectProto.toString;

  /** Used to restore the original '_' reference in '_.noConflict'. */
  var oldDash = root._;

  /** Used to detect if a method is native. */
  var reIsNative = RegExp('^' +
    fnToString.call(hasOwnProperty).replace(/[\\^$.*+?()[\]{}|]/g, '\\$&')
    .replace(/hasOwnProperty|(function).*?(?=\\\()| for .+?(?=\\\])/g, '$1.*?') + '$'
  );

  /** Native method references. */
  var ArrayBuffer = context.ArrayBuffer,
      clearTimeout = context.clearTimeout,
      parseFloat = context.parseFloat,
      pow = Math.pow,
      propertyIsEnumerable = objectProto.propertyIsEnumerable,
      Set = getNative(context, 'Set'),
      setTimeout = context.setTimeout,
      splice = arrayProto.splice,
      Uint8Array = context.Uint8Array,
      WeakMap = getNative(context, 'WeakMap');

  /* Native method references for those with the same name as other 'lodash' methods. */
  var nativeCeil = Math.ceil,
      nativeCreate = getNative(Object, 'create'),
      nativeFloor = Math.floor,
      nativeIsArray = getNative(Array, 'isArray'),
      nativeIsFinite = context.isFinite,
      nativeKeys = getNative(Object, 'keys'),
      nativeMax = Math.max,
      nativeMin = Math.min,
      nativeNow = getNative(Date, 'now'),
      nativeParseInt = context.parseInt,
      nativeRandom = Math.random;

  /** Used as references for '-Infinity' and 'Infinity'. */
  var NEGATIVE_INFINITY = Number.NEGATIVE_INFINITY,
      POSITIVE_INFINITY = Number.POSITIVE_INFINITY;

  /** Used as references for the maximum length and index of an array. */
  var MAX_ARRAY_LENGTH = 4294967295,
      MAX_ARRAY_INDEX = MAX_ARRAY_LENGTH - 1,
      HALF_MAX_ARRAY_LENGTH = MAX_ARRAY_LENGTH >>> 1;

  /**
   * Used as the [maximum length](http://ecma-international.org/ecma-262/6.0/#sec-number.max_safe_integer)
   * of an array-like value.
   */
  var MAX_SAFE_INTEGER = 9007199254740991;

  /** Used to store function metadata. */
  var metaMap = WeakMap && new WeakMap;

  /** Used to lookup unminified function names. */
  var realNames = {};

  /*------------------------------------------------------------------------*/

  /**
   * Creates a 'lodash' object which wraps 'value' to enable implicit chaining.
   * Methods that operate on and return arrays, collections, and functions can
   * be chained together. Methods that retrieve a single value or may return a
   * primitive value will automatically end the chain returning the unwrapped
   * value. Explicit chaining may be enabled using '_.chain'. The execution of
   * chained methods is lazy, that is, execution is deferred until '_#value'
   * is implicitly or explicitly called.
   *
   * Lazy evaluation allows several methods to support shortcut fusion. Shortcut ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.sample"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>sample (collection, n, guard)](#apidoc.element.lodash-node.sample)
- description and source-code
```javascript
function sample(collection, n, guard) {
  if (guard ? isIterateeCall(collection, n, guard) : n == null) {
    collection = toIterable(collection);
    var length = collection.length;
    return length > 0 ? collection[baseRandom(0, length - 1)] : undefined;
  }
  var index = -1,
      result = toArray(collection),
      length = result.length,
      lastIndex = length - 1;

  n = nativeMin(n < 0 ? 0 : (+n || 0), length);
  while (++index < n) {
    var rand = baseRandom(index, lastIndex),
        value = result[rand];

    result[rand] = result[index];
    result[index] = value;
  }
  result.length = n;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.select"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>select (collection, predicate, thisArg)](#apidoc.element.lodash-node.select)
- description and source-code
```javascript
function filter(collection, predicate, thisArg) {
  var func = isArray(collection) ? arrayFilter : baseFilter;
  predicate = getCallback(predicate, thisArg, 3);
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.set"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>set (object, path, value)](#apidoc.element.lodash-node.set)
- description and source-code
```javascript
function set(object, path, value) {
  if (object == null) {
    return object;
  }
  var pathKey = (path + '');
  path = (object[pathKey] != null || isKey(path, object)) ? [pathKey] : toPath(path);

  var index = -1,
      length = path.length,
      lastIndex = length - 1,
      nested = object;

  while (nested != null && ++index < length) {
    var key = path[index];
    if (isObject(nested)) {
      if (index == lastIndex) {
        nested[key] = value;
      } else if (nested[key] == null) {
        nested[key] = isIndex(path[index + 1]) ? [] : {};
      }
    }
    nested = nested[key];
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.shuffle"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>shuffle (collection)](#apidoc.element.lodash-node.shuffle)
- description and source-code
```javascript
function shuffle(collection) {
  return sample(collection, POSITIVE_INFINITY);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.size"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>size (collection)](#apidoc.element.lodash-node.size)
- description and source-code
```javascript
function size(collection) {
  var length = collection ? getLength(collection) : 0;
  return isLength(length) ? length : keys(collection).length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.slice"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>slice (array, start, end)](#apidoc.element.lodash-node.slice)
- description and source-code
```javascript
function slice(array, start, end) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (end && typeof end != 'number' && isIterateeCall(array, start, end)) {
    start = 0;
    end = length;
  }
  return baseSlice(array, start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.snakeCase"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>snakeCase (string)](#apidoc.element.lodash-node.snakeCase)
- description and source-code
```javascript
snakeCase = function (string) {
  var index = -1,
      array = words(deburr(string)),
      length = array.length,
      result = '';

  while (++index < length) {
    result = callback(result, array[index], index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.some"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>some (collection, predicate, thisArg)](#apidoc.element.lodash-node.some)
- description and source-code
```javascript
function some(collection, predicate, thisArg) {
  var func = isArray(collection) ? arraySome : baseSome;
  if (thisArg && isIterateeCall(collection, predicate, thisArg)) {
    predicate = undefined;
  }
  if (typeof predicate != 'function' || thisArg !== undefined) {
    predicate = getCallback(predicate, thisArg, 3);
  }
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.sortBy"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>sortBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.sortBy)
- description and source-code
```javascript
function sortBy(collection, iteratee, thisArg) {
  if (collection == null) {
    return [];
  }
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  var index = -1;
  iteratee = getCallback(iteratee, thisArg, 3);

  var result = baseMap(collection, function(value, key, collection) {
    return { 'criteria': iteratee(value, key, collection), 'index': ++index, 'value': value };
  });
  return baseSortBy(result, compareAscending);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.sortByAll"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>sortByAll ()](#apidoc.element.lodash-node.sortByAll)
- description and source-code
```javascript
sortByAll = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.sortByOrder"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>sortByOrder (collection, iteratees, orders, guard)](#apidoc.element.lodash-node.sortByOrder)
- description and source-code
```javascript
function sortByOrder(collection, iteratees, orders, guard) {
  if (collection == null) {
    return [];
  }
  if (guard && isIterateeCall(iteratees, orders, guard)) {
    orders = undefined;
  }
  if (!isArray(iteratees)) {
    iteratees = iteratees == null ? [] : [iteratees];
  }
  if (!isArray(orders)) {
    orders = orders == null ? [] : [orders];
  }
  return baseSortByOrder(collection, iteratees, orders);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.sortedIndex"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>sortedIndex (array, value, iteratee, thisArg)](#apidoc.element.lodash-node.sortedIndex)
- description and source-code
```javascript
sortedIndex = function (array, value, iteratee, thisArg) {
  var callback = getCallback(iteratee);
  return (iteratee == null && callback === baseCallback)
    ? binaryIndex(array, value, retHighest)
    : binaryIndexBy(array, value, callback(iteratee, thisArg, 1), retHighest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.sortedLastIndex"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>sortedLastIndex (array, value, iteratee, thisArg)](#apidoc.element.lodash-node.sortedLastIndex)
- description and source-code
```javascript
sortedLastIndex = function (array, value, iteratee, thisArg) {
  var callback = getCallback(iteratee);
  return (iteratee == null && callback === baseCallback)
    ? binaryIndex(array, value, retHighest)
    : binaryIndexBy(array, value, callback(iteratee, thisArg, 1), retHighest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.spread"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>spread (func)](#apidoc.element.lodash-node.spread)
- description and source-code
```javascript
function spread(func) {
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  return function(array) {
    return func.apply(this, array);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.startCase"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>startCase (string)](#apidoc.element.lodash-node.startCase)
- description and source-code
```javascript
startCase = function (string) {
  var index = -1,
      array = words(deburr(string)),
      length = array.length,
      result = '';

  while (++index < length) {
    result = callback(result, array[index], index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.startsWith"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>startsWith (string, target, position)](#apidoc.element.lodash-node.startsWith)
- description and source-code
```javascript
function startsWith(string, target, position) {
  string = baseToString(string);
  position = position == null
    ? 0
    : nativeMin(position < 0 ? 0 : (+position || 0), string.length);

  return string.lastIndexOf(target, position) == position;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.sum"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>sum (collection, iteratee, thisArg)](#apidoc.element.lodash-node.sum)
- description and source-code
```javascript
function sum(collection, iteratee, thisArg) {
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  iteratee = getCallback(iteratee, thisArg, 3);
  return iteratee.length == 1
    ? arraySum(isArray(collection) ? collection : toIterable(collection), iteratee)
    : baseSum(collection, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.tail"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>tail (array)](#apidoc.element.lodash-node.tail)
- description and source-code
```javascript
function rest(array) {
  return drop(array, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.take"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>take (array, n, guard)](#apidoc.element.lodash-node.take)
- description and source-code
```javascript
function take(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (guard ? isIterateeCall(array, n, guard) : n == null) {
    n = 1;
  }
  return baseSlice(array, 0, n < 0 ? 0 : n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.takeRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>takeRight (array, n, guard)](#apidoc.element.lodash-node.takeRight)
- description and source-code
```javascript
function takeRight(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (guard ? isIterateeCall(array, n, guard) : n == null) {
    n = 1;
  }
  n = length - (+n || 0);
  return baseSlice(array, n < 0 ? 0 : n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.takeRightWhile"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>takeRightWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.takeRightWhile)
- description and source-code
```javascript
function takeRightWhile(array, predicate, thisArg) {
  return (array && array.length)
    ? baseWhile(array, getCallback(predicate, thisArg, 3), false, true)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.takeWhile"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>takeWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.takeWhile)
- description and source-code
```javascript
function takeWhile(array, predicate, thisArg) {
  return (array && array.length)
    ? baseWhile(array, getCallback(predicate, thisArg, 3))
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.tap"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>tap (value, interceptor, thisArg)](#apidoc.element.lodash-node.tap)
- description and source-code
```javascript
function tap(value, interceptor, thisArg) {
  interceptor.call(thisArg, value);
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.template"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>template (string, options, otherOptions)](#apidoc.element.lodash-node.template)
- description and source-code
```javascript
function template(string, options, otherOptions) {
  // Based on John Resig's 'tmpl' implementation (http://ejohn.org/blog/javascript-micro-templating/)
  // and Laura Doktorova's doT.js (https://github.com/olado/doT).
  var settings = lodash.templateSettings;

  if (otherOptions && isIterateeCall(string, options, otherOptions)) {
    options = otherOptions = undefined;
  }
  string = baseToString(string);
  options = assignWith(baseAssign({}, otherOptions || options), settings, assignOwnDefaults);

  var imports = assignWith(baseAssign({}, options.imports), settings.imports, assignOwnDefaults),
      importsKeys = keys(imports),
      importsValues = baseValues(imports, importsKeys);

  var isEscaping,
      isEvaluating,
      index = 0,
      interpolate = options.interpolate || reNoMatch,
      source = "__p += '";

  // Compile the regexp to match each delimiter.
  var reDelimiters = RegExp(
    (options.escape || reNoMatch).source + '|' +
    interpolate.source + '|' +
    (interpolate === reInterpolate ? reEsTemplate : reNoMatch).source + '|' +
    (options.evaluate || reNoMatch).source + '|$'
  , 'g');

  // Use a sourceURL for easier debugging.
  var sourceURL = '//# sourceURL=' +
    ('sourceURL' in options
      ? options.sourceURL
      : ('lodash.templateSources[' + (++templateCounter) + ']')
    ) + '\n';

  string.replace(reDelimiters, function(match, escapeValue, interpolateValue, esTemplateValue, evaluateValue, offset) {
    interpolateValue || (interpolateValue = esTemplateValue);

    // Escape characters that can't be included in string literals.
    source += string.slice(index, offset).replace(reUnescapedString, escapeStringChar);

    // Replace delimiters with snippets.
    if (escapeValue) {
      isEscaping = true;
      source += "' +\n__e(" + escapeValue + ") +\n'";
    }
    if (evaluateValue) {
      isEvaluating = true;
      source += "';\n" + evaluateValue + ";\n__p += '";
    }
    if (interpolateValue) {
      source += "' +\n((__t = (" + interpolateValue + ")) == null ? '' : __t) +\n'";
    }
    index = offset + match.length;

    // The JS engine embedded in Adobe products requires returning the 'match'
    // string in order to produce the correct 'offset' value.
    return match;
  });

  source += "';\n";

  // If 'variable' is not specified wrap a with-statement around the generated
  // code to add the data object to the top of the scope chain.
  var variable = options.variable;
  if (!variable) {
    source = 'with (obj) {\n' + source + '\n}\n';
  }
  // Cleanup code by stripping empty strings.
  source = (isEvaluating ? source.replace(reEmptyStringLeading, '') : source)
    .replace(reEmptyStringMiddle, '$1')
    .replace(reEmptyStringTrailing, '$1;');

  // Frame code as the function body.
  source = 'function(' + (variable || 'obj') + ') {\n' +
    (variable
      ? ''
      : 'obj || (obj = {});\n'
    ) +
    "var __t, __p = ''" +
    (isEscaping
       ? ', __e = _.escape'
       : ''
    ) +
    (isEvaluating
      ? ', __j = Array.prototype.join;\n' +
        "function print() { __p += __j.call(arguments, '') }\n"
      : ';\n'
    ) +
    source +
    'return __p\n}';

  var result = attempt(function() {
    return Function(importsKeys, sourceURL + 'return ' + source).apply(undefined, importsValues);
  });

  // Provide the compiled function's source by its 'toString' method or
  // the 'source' property as a convenience for inlining compiled templates.
  result.source = source;
  if (isError(result)) {
    throw result;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.throttle"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>throttle (func, wait, options)](#apidoc.element.lodash-node.throttle)
- description and source-code
```javascript
function throttle(func, wait, options) {
  var leading = true,
      trailing = true;

  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  if (options === false) {
    leading = false;
  } else if (isObject(options)) {
    leading = 'leading' in options ? !!options.leading : leading;
    trailing = 'trailing' in options ? !!options.trailing : trailing;
  }
  return debounce(func, wait, { 'leading': leading, 'maxWait': +wait, 'trailing': trailing });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.thru"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>thru (value, interceptor, thisArg)](#apidoc.element.lodash-node.thru)
- description and source-code
```javascript
function thru(value, interceptor, thisArg) {
  return interceptor.call(thisArg, value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.times"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>times (n, iteratee, thisArg)](#apidoc.element.lodash-node.times)
- description and source-code
```javascript
function times(n, iteratee, thisArg) {
  n = nativeFloor(n);

  // Exit early to avoid a JSC JIT bug in Safari 8
  // where 'Array(0)' is treated as 'Array(1)'.
  if (n < 1 || !nativeIsFinite(n)) {
    return [];
  }
  var index = -1,
      result = Array(nativeMin(n, MAX_ARRAY_LENGTH));

  iteratee = bindCallback(iteratee, thisArg, 1);
  while (++index < n) {
    if (index < MAX_ARRAY_LENGTH) {
      result[index] = iteratee(index);
    } else {
      iteratee(index);
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.toArray"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>toArray (value)](#apidoc.element.lodash-node.toArray)
- description and source-code
```javascript
function toArray(value) {
  var length = value ? getLength(value) : 0;
  if (!isLength(length)) {
    return values(value);
  }
  if (!length) {
    return [];
  }
  return arrayCopy(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.toPlainObject"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>toPlainObject (value)](#apidoc.element.lodash-node.toPlainObject)
- description and source-code
```javascript
function toPlainObject(value) {
  return baseCopy(value, keysIn(value));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.transform"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>transform (object, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.transform)
- description and source-code
```javascript
function transform(object, iteratee, accumulator, thisArg) {
  var isArr = isArray(object) || isTypedArray(object);
  iteratee = getCallback(iteratee, thisArg, 4);

  if (accumulator == null) {
    if (isArr || isObject(object)) {
      var Ctor = object.constructor;
      if (isArr) {
        accumulator = isArray(object) ? new Ctor : [];
      } else {
        accumulator = baseCreate(isFunction(Ctor) ? Ctor.prototype : undefined);
      }
    } else {
      accumulator = {};
    }
  }
  (isArr ? arrayEach : baseForOwn)(object, function(value, index, object) {
    return iteratee(accumulator, value, index, object);
  });
  return accumulator;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.trim"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>trim (string, chars, guard)](#apidoc.element.lodash-node.trim)
- description and source-code
```javascript
function trim(string, chars, guard) {
  var value = string;
  string = baseToString(string);
  if (!string) {
    return string;
  }
  if (guard ? isIterateeCall(value, chars, guard) : chars == null) {
    return string.slice(trimmedLeftIndex(string), trimmedRightIndex(string) + 1);
  }
  chars = (chars + '');
  return string.slice(charsLeftIndex(string, chars), charsRightIndex(string, chars) + 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.trimLeft"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>trimLeft (string, chars, guard)](#apidoc.element.lodash-node.trimLeft)
- description and source-code
```javascript
function trimLeft(string, chars, guard) {
  var value = string;
  string = baseToString(string);
  if (!string) {
    return string;
  }
  if (guard ? isIterateeCall(value, chars, guard) : chars == null) {
    return string.slice(trimmedLeftIndex(string));
  }
  return string.slice(charsLeftIndex(string, (chars + '')));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.trimRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>trimRight (string, chars, guard)](#apidoc.element.lodash-node.trimRight)
- description and source-code
```javascript
function trimRight(string, chars, guard) {
  var value = string;
  string = baseToString(string);
  if (!string) {
    return string;
  }
  if (guard ? isIterateeCall(value, chars, guard) : chars == null) {
    return string.slice(0, trimmedRightIndex(string) + 1);
  }
  return string.slice(0, charsRightIndex(string, (chars + '')) + 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.trunc"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>trunc (string, options, guard)](#apidoc.element.lodash-node.trunc)
- description and source-code
```javascript
function trunc(string, options, guard) {
  if (guard && isIterateeCall(string, options, guard)) {
    options = undefined;
  }
  var length = DEFAULT_TRUNC_LENGTH,
      omission = DEFAULT_TRUNC_OMISSION;

  if (options != null) {
    if (isObject(options)) {
      var separator = 'separator' in options ? options.separator : separator;
      length = 'length' in options ? (+options.length || 0) : length;
      omission = 'omission' in options ? baseToString(options.omission) : omission;
    } else {
      length = +options || 0;
    }
  }
  string = baseToString(string);
  if (length >= string.length) {
    return string;
  }
  var end = length - omission.length;
  if (end < 1) {
    return omission;
  }
  var result = string.slice(0, end);
  if (separator == null) {
    return result + omission;
  }
  if (isRegExp(separator)) {
    if (string.slice(end).search(separator)) {
      var match,
          newEnd,
          substring = string.slice(0, end);

      if (!separator.global) {
        separator = RegExp(separator.source, (reFlags.exec(separator) || '') + 'g');
      }
      separator.lastIndex = 0;
      while ((match = separator.exec(substring))) {
        newEnd = match.index;
      }
      result = result.slice(0, newEnd == null ? end : newEnd);
    }
  } else if (string.indexOf(separator, end) != end) {
    var index = result.lastIndexOf(separator);
    if (index > -1) {
      result = result.slice(0, index);
    }
  }
  return result + omission;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.unescape"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>unescape (string)](#apidoc.element.lodash-node.unescape)
- description and source-code
```javascript
function unescape(string) {
  string = baseToString(string);
  return (string && reHasEscapedHtml.test(string))
    ? string.replace(reEscapedHtml, unescapeHtmlChar)
    : string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.union"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>union ()](#apidoc.element.lodash-node.union)
- description and source-code
```javascript
union = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.uniq"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>uniq (array, isSorted, iteratee, thisArg)](#apidoc.element.lodash-node.uniq)
- description and source-code
```javascript
function uniq(array, isSorted, iteratee, thisArg) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (isSorted != null && typeof isSorted != 'boolean') {
    thisArg = iteratee;
    iteratee = isIterateeCall(array, isSorted, thisArg) ? undefined : isSorted;
    isSorted = false;
  }
  var callback = getCallback();
  if (!(iteratee == null && callback === baseCallback)) {
    iteratee = callback(iteratee, thisArg, 3);
  }
  return (isSorted && getIndexOf() === baseIndexOf)
    ? sortedUniq(array, iteratee)
    : baseUniq(array, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.unique"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>unique (array, isSorted, iteratee, thisArg)](#apidoc.element.lodash-node.unique)
- description and source-code
```javascript
function uniq(array, isSorted, iteratee, thisArg) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (isSorted != null && typeof isSorted != 'boolean') {
    thisArg = iteratee;
    iteratee = isIterateeCall(array, isSorted, thisArg) ? undefined : isSorted;
    isSorted = false;
  }
  var callback = getCallback();
  if (!(iteratee == null && callback === baseCallback)) {
    iteratee = callback(iteratee, thisArg, 3);
  }
  return (isSorted && getIndexOf() === baseIndexOf)
    ? sortedUniq(array, iteratee)
    : baseUniq(array, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.uniqueId"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>uniqueId (prefix)](#apidoc.element.lodash-node.uniqueId)
- description and source-code
```javascript
function uniqueId(prefix) {
  var id = ++idCounter;
  return baseToString(prefix) + id;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.unzip"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>unzip (array)](#apidoc.element.lodash-node.unzip)
- description and source-code
```javascript
function unzip(array) {
  if (!(array && array.length)) {
    return [];
  }
  var index = -1,
      length = 0;

  array = arrayFilter(array, function(group) {
    if (isArrayLike(group)) {
      length = nativeMax(group.length, length);
      return true;
    }
  });
  var result = Array(length);
  while (++index < length) {
    result[index] = arrayMap(array, baseProperty(index));
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.unzipWith"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>unzipWith (array, iteratee, thisArg)](#apidoc.element.lodash-node.unzipWith)
- description and source-code
```javascript
function unzipWith(array, iteratee, thisArg) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  var result = unzip(array);
  if (iteratee == null) {
    return result;
  }
  iteratee = bindCallback(iteratee, thisArg, 4);
  return arrayMap(result, function(group) {
    return arrayReduce(group, iteratee, undefined, true);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.values"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>values (object)](#apidoc.element.lodash-node.values)
- description and source-code
```javascript
function values(object) {
  return baseValues(object, keys(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.valuesIn"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>valuesIn (object)](#apidoc.element.lodash-node.valuesIn)
- description and source-code
```javascript
function valuesIn(object) {
  return baseValues(object, keysIn(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.where"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>where (collection, source)](#apidoc.element.lodash-node.where)
- description and source-code
```javascript
function where(collection, source) {
  return filter(collection, baseMatches(source));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.without"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>without ()](#apidoc.element.lodash-node.without)
- description and source-code
```javascript
without = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.words"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>words (string, pattern, guard)](#apidoc.element.lodash-node.words)
- description and source-code
```javascript
function words(string, pattern, guard) {
  if (guard && isIterateeCall(string, pattern, guard)) {
    pattern = undefined;
  }
  string = baseToString(string);
  return string.match(pattern || reWords) || [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.wrap"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>wrap (value, wrapper)](#apidoc.element.lodash-node.wrap)
- description and source-code
```javascript
function wrap(value, wrapper) {
  wrapper = wrapper == null ? identity : wrapper;
  return createWrapper(wrapper, PARTIAL_FLAG, undefined, [value], []);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.xor"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>xor ()](#apidoc.element.lodash-node.xor)
- description and source-code
```javascript
function xor() {
  var index = -1,
      length = arguments.length;

  while (++index < length) {
    var array = arguments[index];
    if (isArrayLike(array)) {
      var result = result
        ? arrayPush(baseDifference(result, array), baseDifference(array, result))
        : array;
    }
  }
  return result ? baseUniq(result) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.zip"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>zip ()](#apidoc.element.lodash-node.zip)
- description and source-code
```javascript
zip = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.zipObject"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>zipObject (props, values)](#apidoc.element.lodash-node.zipObject)
- description and source-code
```javascript
function zipObject(props, values) {
  var index = -1,
      length = props ? props.length : 0,
      result = {};

  if (length && !values && !isArray(props[0])) {
    values = [];
  }
  while (++index < length) {
    var key = props[index];
    if (values) {
      result[key] = values[index];
    } else if (key) {
      result[key[0]] = key[1];
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.zipWith"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>zipWith ()](#apidoc.element.lodash-node.zipWith)
- description and source-code
```javascript
zipWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.array"></a>[module lodash-node.array](#apidoc.module.lodash-node.array)

#### <a name="apidoc.element.lodash-node.array.chunk"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>chunk (array, size, guard)](#apidoc.element.lodash-node.array.chunk)
- description and source-code
```javascript
function chunk(array, size, guard) {
  if (guard ? isIterateeCall(array, size, guard) : size == null) {
    size = 1;
  } else {
    size = nativeMax(nativeFloor(size) || 1, 1);
  }
  var index = 0,
      length = array ? array.length : 0,
      resIndex = -1,
      result = Array(nativeCeil(length / size));

  while (index < length) {
    result[++resIndex] = baseSlice(array, index, (index += size));
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.compact"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>compact (array)](#apidoc.element.lodash-node.array.compact)
- description and source-code
```javascript
function compact(array) {
  var index = -1,
      length = array ? array.length : 0,
      resIndex = -1,
      result = [];

  while (++index < length) {
    var value = array[index];
    if (value) {
      result[++resIndex] = value;
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.difference"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>difference ()](#apidoc.element.lodash-node.array.difference)
- description and source-code
```javascript
difference = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.drop"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>drop (array, n, guard)](#apidoc.element.lodash-node.array.drop)
- description and source-code
```javascript
function drop(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (guard ? isIterateeCall(array, n, guard) : n == null) {
    n = 1;
  }
  return baseSlice(array, n < 0 ? 0 : n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.dropRight"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>dropRight (array, n, guard)](#apidoc.element.lodash-node.array.dropRight)
- description and source-code
```javascript
function dropRight(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (guard ? isIterateeCall(array, n, guard) : n == null) {
    n = 1;
  }
  n = length - (+n || 0);
  return baseSlice(array, 0, n < 0 ? 0 : n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.dropRightWhile"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>dropRightWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.array.dropRightWhile)
- description and source-code
```javascript
function dropRightWhile(array, predicate, thisArg) {
  return (array && array.length)
    ? baseWhile(array, baseCallback(predicate, thisArg, 3), true, true)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.dropWhile"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>dropWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.array.dropWhile)
- description and source-code
```javascript
function dropWhile(array, predicate, thisArg) {
  return (array && array.length)
    ? baseWhile(array, baseCallback(predicate, thisArg, 3), true)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.fill"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>fill (array, value, start, end)](#apidoc.element.lodash-node.array.fill)
- description and source-code
```javascript
function fill(array, value, start, end) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (start && typeof start != 'number' && isIterateeCall(array, value, start)) {
    start = 0;
    end = length;
  }
  return baseFill(array, value, start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.findIndex"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>findIndex (array, predicate, thisArg)](#apidoc.element.lodash-node.array.findIndex)
- description and source-code
```javascript
findIndex = function (array, predicate, thisArg) {
  if (!(array && array.length)) {
    return -1;
  }
  predicate = baseCallback(predicate, thisArg, 3);
  return baseFindIndex(array, predicate, fromRight);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.findLastIndex"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>findLastIndex (array, predicate, thisArg)](#apidoc.element.lodash-node.array.findLastIndex)
- description and source-code
```javascript
findLastIndex = function (array, predicate, thisArg) {
  if (!(array && array.length)) {
    return -1;
  }
  predicate = baseCallback(predicate, thisArg, 3);
  return baseFindIndex(array, predicate, fromRight);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.first"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>first (array)](#apidoc.element.lodash-node.array.first)
- description and source-code
```javascript
function first(array) {
  return array ? array[0] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.flatten"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>flatten (array, isDeep, guard)](#apidoc.element.lodash-node.array.flatten)
- description and source-code
```javascript
function flatten(array, isDeep, guard) {
  var length = array ? array.length : 0;
  if (guard && isIterateeCall(array, isDeep, guard)) {
    isDeep = false;
  }
  return length ? baseFlatten(array, isDeep) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.flattenDeep"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>flattenDeep (array)](#apidoc.element.lodash-node.array.flattenDeep)
- description and source-code
```javascript
function flattenDeep(array) {
  var length = array ? array.length : 0;
  return length ? baseFlatten(array, true) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.head"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>head (array)](#apidoc.element.lodash-node.array.head)
- description and source-code
```javascript
function first(array) {
  return array ? array[0] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.indexOf"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>indexOf (array, value, fromIndex)](#apidoc.element.lodash-node.array.indexOf)
- description and source-code
```javascript
function indexOf(array, value, fromIndex) {
  var length = array ? array.length : 0;
  if (!length) {
    return -1;
  }
  if (typeof fromIndex == 'number') {
    fromIndex = fromIndex < 0 ? nativeMax(length + fromIndex, 0) : fromIndex;
  } else if (fromIndex) {
    var index = binaryIndex(array, value);
    if (index < length &&
        (value === value ? (value === array[index]) : (array[index] !== array[index]))) {
      return index;
    }
    return -1;
  }
  return baseIndexOf(array, value, fromIndex || 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.initial"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>initial (array)](#apidoc.element.lodash-node.array.initial)
- description and source-code
```javascript
function initial(array) {
  return dropRight(array, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.intersection"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>intersection ()](#apidoc.element.lodash-node.array.intersection)
- description and source-code
```javascript
intersection = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.last"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>last (array)](#apidoc.element.lodash-node.array.last)
- description and source-code
```javascript
function last(array) {
  var length = array ? array.length : 0;
  return length ? array[length - 1] : undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.lastIndexOf"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>lastIndexOf (array, value, fromIndex)](#apidoc.element.lodash-node.array.lastIndexOf)
- description and source-code
```javascript
function lastIndexOf(array, value, fromIndex) {
  var length = array ? array.length : 0;
  if (!length) {
    return -1;
  }
  var index = length;
  if (typeof fromIndex == 'number') {
    index = (fromIndex < 0 ? nativeMax(length + fromIndex, 0) : nativeMin(fromIndex || 0, length - 1)) + 1;
  } else if (fromIndex) {
    index = binaryIndex(array, value, true) - 1;
    var other = array[index];
    if (value === value ? (value === other) : (other !== other)) {
      return index;
    }
    return -1;
  }
  if (value !== value) {
    return indexOfNaN(array, index, true);
  }
  while (index--) {
    if (array[index] === value) {
      return index;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.object"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>object (props, values)](#apidoc.element.lodash-node.array.object)
- description and source-code
```javascript
function zipObject(props, values) {
  var index = -1,
      length = props ? props.length : 0,
      result = {};

  if (length && !values && !isArray(props[0])) {
    values = [];
  }
  while (++index < length) {
    var key = props[index];
    if (values) {
      result[key] = values[index];
    } else if (key) {
      result[key[0]] = key[1];
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.pull"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>pull ()](#apidoc.element.lodash-node.array.pull)
- description and source-code
```javascript
function pull() {
  var args = arguments,
      array = args[0];

  if (!(array && array.length)) {
    return array;
  }
  var index = 0,
      indexOf = baseIndexOf,
      length = args.length;

  while (++index < length) {
    var fromIndex = 0,
        value = args[index];

    while ((fromIndex = indexOf(array, value, fromIndex)) > -1) {
      splice.call(array, fromIndex, 1);
    }
  }
  return array;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.pullAt"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>pullAt ()](#apidoc.element.lodash-node.array.pullAt)
- description and source-code
```javascript
pullAt = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.remove"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>remove (array, predicate, thisArg)](#apidoc.element.lodash-node.array.remove)
- description and source-code
```javascript
function remove(array, predicate, thisArg) {
  var result = [];
  if (!(array && array.length)) {
    return result;
  }
  var index = -1,
      indexes = [],
      length = array.length;

  predicate = baseCallback(predicate, thisArg, 3);
  while (++index < length) {
    var value = array[index];
    if (predicate(value, index, array)) {
      result.push(value);
      indexes.push(index);
    }
  }
  basePullAt(array, indexes);
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.rest"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>rest (array)](#apidoc.element.lodash-node.array.rest)
- description and source-code
```javascript
function rest(array) {
  return drop(array, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.slice"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>slice (array, start, end)](#apidoc.element.lodash-node.array.slice)
- description and source-code
```javascript
function slice(array, start, end) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (end && typeof end != 'number' && isIterateeCall(array, start, end)) {
    start = 0;
    end = length;
  }
  return baseSlice(array, start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.sortedIndex"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>sortedIndex (array, value, iteratee, thisArg)](#apidoc.element.lodash-node.array.sortedIndex)
- description and source-code
```javascript
sortedIndex = function (array, value, iteratee, thisArg) {
  return iteratee == null
    ? binaryIndex(array, value, retHighest)
    : binaryIndexBy(array, value, baseCallback(iteratee, thisArg, 1), retHighest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.sortedLastIndex"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>sortedLastIndex (array, value, iteratee, thisArg)](#apidoc.element.lodash-node.array.sortedLastIndex)
- description and source-code
```javascript
sortedLastIndex = function (array, value, iteratee, thisArg) {
  return iteratee == null
    ? binaryIndex(array, value, retHighest)
    : binaryIndexBy(array, value, baseCallback(iteratee, thisArg, 1), retHighest);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.tail"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>tail (array)](#apidoc.element.lodash-node.array.tail)
- description and source-code
```javascript
function rest(array) {
  return drop(array, 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.take"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>take (array, n, guard)](#apidoc.element.lodash-node.array.take)
- description and source-code
```javascript
function take(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (guard ? isIterateeCall(array, n, guard) : n == null) {
    n = 1;
  }
  return baseSlice(array, 0, n < 0 ? 0 : n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.takeRight"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>takeRight (array, n, guard)](#apidoc.element.lodash-node.array.takeRight)
- description and source-code
```javascript
function takeRight(array, n, guard) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (guard ? isIterateeCall(array, n, guard) : n == null) {
    n = 1;
  }
  n = length - (+n || 0);
  return baseSlice(array, n < 0 ? 0 : n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.takeRightWhile"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>takeRightWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.array.takeRightWhile)
- description and source-code
```javascript
function takeRightWhile(array, predicate, thisArg) {
  return (array && array.length)
    ? baseWhile(array, baseCallback(predicate, thisArg, 3), false, true)
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.takeWhile"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>takeWhile (array, predicate, thisArg)](#apidoc.element.lodash-node.array.takeWhile)
- description and source-code
```javascript
function takeWhile(array, predicate, thisArg) {
  return (array && array.length)
    ? baseWhile(array, baseCallback(predicate, thisArg, 3))
    : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.union"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>union ()](#apidoc.element.lodash-node.array.union)
- description and source-code
```javascript
union = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.uniq"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>uniq (array, isSorted, iteratee, thisArg)](#apidoc.element.lodash-node.array.uniq)
- description and source-code
```javascript
function uniq(array, isSorted, iteratee, thisArg) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (isSorted != null && typeof isSorted != 'boolean') {
    thisArg = iteratee;
    iteratee = isIterateeCall(array, isSorted, thisArg) ? undefined : isSorted;
    isSorted = false;
  }
  iteratee = iteratee == null ? iteratee : baseCallback(iteratee, thisArg, 3);
  return (isSorted)
    ? sortedUniq(array, iteratee)
    : baseUniq(array, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.unique"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>unique (array, isSorted, iteratee, thisArg)](#apidoc.element.lodash-node.array.unique)
- description and source-code
```javascript
function uniq(array, isSorted, iteratee, thisArg) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  if (isSorted != null && typeof isSorted != 'boolean') {
    thisArg = iteratee;
    iteratee = isIterateeCall(array, isSorted, thisArg) ? undefined : isSorted;
    isSorted = false;
  }
  iteratee = iteratee == null ? iteratee : baseCallback(iteratee, thisArg, 3);
  return (isSorted)
    ? sortedUniq(array, iteratee)
    : baseUniq(array, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.unzip"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>unzip (array)](#apidoc.element.lodash-node.array.unzip)
- description and source-code
```javascript
function unzip(array) {
  if (!(array && array.length)) {
    return [];
  }
  var index = -1,
      length = 0;

  array = arrayFilter(array, function(group) {
    if (isArrayLike(group)) {
      length = nativeMax(group.length, length);
      return true;
    }
  });
  var result = Array(length);
  while (++index < length) {
    result[index] = arrayMap(array, baseProperty(index));
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.unzipWith"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>unzipWith (array, iteratee, thisArg)](#apidoc.element.lodash-node.array.unzipWith)
- description and source-code
```javascript
function unzipWith(array, iteratee, thisArg) {
  var length = array ? array.length : 0;
  if (!length) {
    return [];
  }
  var result = unzip(array);
  if (iteratee == null) {
    return result;
  }
  iteratee = bindCallback(iteratee, thisArg, 4);
  return arrayMap(result, function(group) {
    return arrayReduce(group, iteratee, undefined, true);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.without"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>without ()](#apidoc.element.lodash-node.array.without)
- description and source-code
```javascript
without = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.xor"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>xor ()](#apidoc.element.lodash-node.array.xor)
- description and source-code
```javascript
function xor() {
  var index = -1,
      length = arguments.length;

  while (++index < length) {
    var array = arguments[index];
    if (isArrayLike(array)) {
      var result = result
        ? arrayPush(baseDifference(result, array), baseDifference(array, result))
        : array;
    }
  }
  return result ? baseUniq(result) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.zip"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>zip ()](#apidoc.element.lodash-node.array.zip)
- description and source-code
```javascript
zip = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.zipObject"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>zipObject (props, values)](#apidoc.element.lodash-node.array.zipObject)
- description and source-code
```javascript
function zipObject(props, values) {
  var index = -1,
      length = props ? props.length : 0,
      result = {};

  if (length && !values && !isArray(props[0])) {
    values = [];
  }
  while (++index < length) {
    var key = props[index];
    if (values) {
      result[key] = values[index];
    } else if (key) {
      result[key[0]] = key[1];
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.array.zipWith"></a>[function <span class="apidocSignatureSpan">lodash-node.array.</span>zipWith ()](#apidoc.element.lodash-node.array.zipWith)
- description and source-code
```javascript
zipWith = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.bind"></a>[module lodash-node.bind](#apidoc.module.lodash-node.bind)

#### <a name="apidoc.element.lodash-node.bind.bind"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>bind ()](#apidoc.element.lodash-node.bind.bind)
- description and source-code
```javascript
function bind() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.bind.placeholder"></a>[function <span class="apidocSignatureSpan">lodash-node.bind.</span>placeholder (value)](#apidoc.element.lodash-node.bind.placeholder)
- description and source-code
```javascript
function lodash(value) {
  if (isObjectLike(value) && !isArray(value) && !(value instanceof LazyWrapper)) {
    if (value instanceof LodashWrapper) {
      return value;
    }
    if (hasOwnProperty.call(value, '__chain__') && hasOwnProperty.call(value, '__wrapped__')) {
      return wrapperClone(value);
    }
  }
  return new LodashWrapper(value);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.bindKey"></a>[module lodash-node.bindKey](#apidoc.module.lodash-node.bindKey)

#### <a name="apidoc.element.lodash-node.bindKey.bindKey"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>bindKey ()](#apidoc.element.lodash-node.bindKey.bindKey)
- description and source-code
```javascript
bindKey = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.bindKey.placeholder"></a>[function <span class="apidocSignatureSpan">lodash-node.bindKey.</span>placeholder (value)](#apidoc.element.lodash-node.bindKey.placeholder)
- description and source-code
```javascript
function lodash(value) {
  if (isObjectLike(value) && !isArray(value) && !(value instanceof LazyWrapper)) {
    if (value instanceof LodashWrapper) {
      return value;
    }
    if (hasOwnProperty.call(value, '__chain__') && hasOwnProperty.call(value, '__wrapped__')) {
      return wrapperClone(value);
    }
  }
  return new LodashWrapper(value);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.chain"></a>[module lodash-node.chain](#apidoc.module.lodash-node.chain)

#### <a name="apidoc.element.lodash-node.chain.chain"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>chain (value)](#apidoc.element.lodash-node.chain.chain)
- description and source-code
```javascript
function chain(value) {
  var result = lodash(value);
  result.__chain__ = true;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.commit"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>commit ()](#apidoc.element.lodash-node.chain.commit)
- description and source-code
```javascript
function wrapperCommit() {
  return new LodashWrapper(this.value(), this.__chain__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.concat"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>concat ()](#apidoc.element.lodash-node.chain.concat)
- description and source-code
```javascript
concat = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.lodash"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>lodash (value)](#apidoc.element.lodash-node.chain.lodash)
- description and source-code
```javascript
function lodash(value) {
  if (isObjectLike(value) && !isArray(value) && !(value instanceof LazyWrapper)) {
    if (value instanceof LodashWrapper) {
      return value;
    }
    if (hasOwnProperty.call(value, '__chain__') && hasOwnProperty.call(value, '__wrapped__')) {
      return wrapperClone(value);
    }
  }
  return new LodashWrapper(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.plant"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>plant (value)](#apidoc.element.lodash-node.chain.plant)
- description and source-code
```javascript
function wrapperPlant(value) {
  var result,
      parent = this;

  while (parent instanceof baseLodash) {
    var clone = wrapperClone(parent);
    if (result) {
      previous.__wrapped__ = clone;
    } else {
      result = clone;
    }
    var previous = clone;
    parent = parent.__wrapped__;
  }
  previous.__wrapped__ = value;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.reverse"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>reverse ()](#apidoc.element.lodash-node.chain.reverse)
- description and source-code
```javascript
function wrapperReverse() {
  var value = this.__wrapped__;

  var interceptor = function(value) {
    return value.reverse();
  };
  if (value instanceof LazyWrapper) {
    var wrapped = value;
    if (this.__actions__.length) {
      wrapped = new LazyWrapper(this);
    }
    wrapped = wrapped.reverse();
    wrapped.__actions__.push({ 'func': thru, 'args': [interceptor], 'thisArg': undefined });
    return new LodashWrapper(wrapped, this.__chain__);
  }
  return this.thru(interceptor);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.run"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>run ()](#apidoc.element.lodash-node.chain.run)
- description and source-code
```javascript
function wrapperValue() {
  return baseWrapperValue(this.__wrapped__, this.__actions__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.tap"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>tap (value, interceptor, thisArg)](#apidoc.element.lodash-node.chain.tap)
- description and source-code
```javascript
function tap(value, interceptor, thisArg) {
  interceptor.call(thisArg, value);
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.thru"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>thru (value, interceptor, thisArg)](#apidoc.element.lodash-node.chain.thru)
- description and source-code
```javascript
function thru(value, interceptor, thisArg) {
  return interceptor.call(thisArg, value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.toJSON"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>toJSON ()](#apidoc.element.lodash-node.chain.toJSON)
- description and source-code
```javascript
function wrapperValue() {
  return baseWrapperValue(this.__wrapped__, this.__actions__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.toString"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>toString ()](#apidoc.element.lodash-node.chain.toString)
- description and source-code
```javascript
function wrapperToString() {
  return (this.value() + '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.value"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>value ()](#apidoc.element.lodash-node.chain.value)
- description and source-code
```javascript
function wrapperValue() {
  return baseWrapperValue(this.__wrapped__, this.__actions__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.valueOf"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>valueOf ()](#apidoc.element.lodash-node.chain.valueOf)
- description and source-code
```javascript
function wrapperValue() {
  return baseWrapperValue(this.__wrapped__, this.__actions__);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.chain.wrapperChain"></a>[function <span class="apidocSignatureSpan">lodash-node.chain.</span>wrapperChain ()](#apidoc.element.lodash-node.chain.wrapperChain)
- description and source-code
```javascript
function wrapperChain() {
  return chain(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.collection"></a>[module lodash-node.collection](#apidoc.module.lodash-node.collection)

#### <a name="apidoc.element.lodash-node.collection.all"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>all (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.all)
- description and source-code
```javascript
function every(collection, predicate, thisArg) {
  var func = isArray(collection) ? arrayEvery : baseEvery;
  if (thisArg && isIterateeCall(collection, predicate, thisArg)) {
    predicate = undefined;
  }
  if (typeof predicate != 'function' || thisArg !== undefined) {
    predicate = baseCallback(predicate, thisArg, 3);
  }
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.any"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>any (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.any)
- description and source-code
```javascript
function some(collection, predicate, thisArg) {
  var func = isArray(collection) ? arraySome : baseSome;
  if (thisArg && isIterateeCall(collection, predicate, thisArg)) {
    predicate = undefined;
  }
  if (typeof predicate != 'function' || thisArg !== undefined) {
    predicate = baseCallback(predicate, thisArg, 3);
  }
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.at"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>at ()](#apidoc.element.lodash-node.collection.at)
- description and source-code
```javascript
at = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.collect"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>collect (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.collect)
- description and source-code
```javascript
function map(collection, iteratee, thisArg) {
  var func = isArray(collection) ? arrayMap : baseMap;
  iteratee = baseCallback(iteratee, thisArg, 3);
  return func(collection, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.contains"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>contains (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.collection.contains)
- description and source-code
```javascript
function includes(collection, target, fromIndex, guard) {
  var length = collection ? getLength(collection) : 0;
  if (!isLength(length)) {
    collection = values(collection);
    length = collection.length;
  }
  if (typeof fromIndex != 'number' || (guard && isIterateeCall(target, fromIndex, guard))) {
    fromIndex = 0;
  } else {
    fromIndex = fromIndex < 0 ? nativeMax(length + fromIndex, 0) : (fromIndex || 0);
  }
  return (typeof collection == 'string' || !isArray(collection) && isString(collection))
    ? (fromIndex <= length && collection.indexOf(target, fromIndex) > -1)
    : (!!length && baseIndexOf(collection, target, fromIndex) > -1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.countBy"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>countBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.countBy)
- description and source-code
```javascript
countBy = function (collection, iteratee, thisArg) {
  var result = initializer ? initializer() : {};
  iteratee = baseCallback(iteratee, thisArg, 3);

  if (isArray(collection)) {
    var index = -1,
        length = collection.length;

    while (++index < length) {
      var value = collection[index];
      setter(result, value, iteratee(value, index, collection), collection);
    }
  } else {
    baseEach(collection, function(value, key, collection) {
      setter(result, value, iteratee(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.detect"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>detect (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.detect)
- description and source-code
```javascript
detect = function (collection, predicate, thisArg) {
  predicate = baseCallback(predicate, thisArg, 3);
  if (isArray(collection)) {
    var index = baseFindIndex(collection, predicate, fromRight);
    return index > -1 ? collection[index] : undefined;
  }
  return baseFind(collection, predicate, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.each"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>each (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.each)
- description and source-code
```javascript
each = function (collection, iteratee, thisArg) {
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee)
    : eachFunc(collection, bindCallback(iteratee, thisArg, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.eachRight"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>eachRight (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.eachRight)
- description and source-code
```javascript
eachRight = function (collection, iteratee, thisArg) {
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee)
    : eachFunc(collection, bindCallback(iteratee, thisArg, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.every"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>every (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.every)
- description and source-code
```javascript
function every(collection, predicate, thisArg) {
  var func = isArray(collection) ? arrayEvery : baseEvery;
  if (thisArg && isIterateeCall(collection, predicate, thisArg)) {
    predicate = undefined;
  }
  if (typeof predicate != 'function' || thisArg !== undefined) {
    predicate = baseCallback(predicate, thisArg, 3);
  }
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.filter"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>filter (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.filter)
- description and source-code
```javascript
function filter(collection, predicate, thisArg) {
  var func = isArray(collection) ? arrayFilter : baseFilter;
  predicate = baseCallback(predicate, thisArg, 3);
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.find"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>find (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.find)
- description and source-code
```javascript
find = function (collection, predicate, thisArg) {
  predicate = baseCallback(predicate, thisArg, 3);
  if (isArray(collection)) {
    var index = baseFindIndex(collection, predicate, fromRight);
    return index > -1 ? collection[index] : undefined;
  }
  return baseFind(collection, predicate, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.findLast"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>findLast (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.findLast)
- description and source-code
```javascript
findLast = function (collection, predicate, thisArg) {
  predicate = baseCallback(predicate, thisArg, 3);
  if (isArray(collection)) {
    var index = baseFindIndex(collection, predicate, fromRight);
    return index > -1 ? collection[index] : undefined;
  }
  return baseFind(collection, predicate, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.findWhere"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>findWhere (collection, source)](#apidoc.element.lodash-node.collection.findWhere)
- description and source-code
```javascript
function findWhere(collection, source) {
  return find(collection, baseMatches(source));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.foldl"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>foldl (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.collection.foldl)
- description and source-code
```javascript
foldl = function (collection, iteratee, accumulator, thisArg) {
  var initFromArray = arguments.length < 3;
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee, accumulator, initFromArray)
    : baseReduce(collection, baseCallback(iteratee, thisArg, 4), accumulator, initFromArray, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.foldr"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>foldr (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.collection.foldr)
- description and source-code
```javascript
foldr = function (collection, iteratee, accumulator, thisArg) {
  var initFromArray = arguments.length < 3;
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee, accumulator, initFromArray)
    : baseReduce(collection, baseCallback(iteratee, thisArg, 4), accumulator, initFromArray, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.forEach"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>forEach (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.forEach)
- description and source-code
```javascript
forEach = function (collection, iteratee, thisArg) {
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee)
    : eachFunc(collection, bindCallback(iteratee, thisArg, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.forEachRight"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>forEachRight (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.forEachRight)
- description and source-code
```javascript
forEachRight = function (collection, iteratee, thisArg) {
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee)
    : eachFunc(collection, bindCallback(iteratee, thisArg, 3));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.groupBy"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>groupBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.groupBy)
- description and source-code
```javascript
groupBy = function (collection, iteratee, thisArg) {
  var result = initializer ? initializer() : {};
  iteratee = baseCallback(iteratee, thisArg, 3);

  if (isArray(collection)) {
    var index = -1,
        length = collection.length;

    while (++index < length) {
      var value = collection[index];
      setter(result, value, iteratee(value, index, collection), collection);
    }
  } else {
    baseEach(collection, function(value, key, collection) {
      setter(result, value, iteratee(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.include"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>include (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.collection.include)
- description and source-code
```javascript
function includes(collection, target, fromIndex, guard) {
  var length = collection ? getLength(collection) : 0;
  if (!isLength(length)) {
    collection = values(collection);
    length = collection.length;
  }
  if (typeof fromIndex != 'number' || (guard && isIterateeCall(target, fromIndex, guard))) {
    fromIndex = 0;
  } else {
    fromIndex = fromIndex < 0 ? nativeMax(length + fromIndex, 0) : (fromIndex || 0);
  }
  return (typeof collection == 'string' || !isArray(collection) && isString(collection))
    ? (fromIndex <= length && collection.indexOf(target, fromIndex) > -1)
    : (!!length && baseIndexOf(collection, target, fromIndex) > -1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.includes"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>includes (collection, target, fromIndex, guard)](#apidoc.element.lodash-node.collection.includes)
- description and source-code
```javascript
function includes(collection, target, fromIndex, guard) {
  var length = collection ? getLength(collection) : 0;
  if (!isLength(length)) {
    collection = values(collection);
    length = collection.length;
  }
  if (typeof fromIndex != 'number' || (guard && isIterateeCall(target, fromIndex, guard))) {
    fromIndex = 0;
  } else {
    fromIndex = fromIndex < 0 ? nativeMax(length + fromIndex, 0) : (fromIndex || 0);
  }
  return (typeof collection == 'string' || !isArray(collection) && isString(collection))
    ? (fromIndex <= length && collection.indexOf(target, fromIndex) > -1)
    : (!!length && baseIndexOf(collection, target, fromIndex) > -1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.indexBy"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>indexBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.indexBy)
- description and source-code
```javascript
indexBy = function (collection, iteratee, thisArg) {
  var result = initializer ? initializer() : {};
  iteratee = baseCallback(iteratee, thisArg, 3);

  if (isArray(collection)) {
    var index = -1,
        length = collection.length;

    while (++index < length) {
      var value = collection[index];
      setter(result, value, iteratee(value, index, collection), collection);
    }
  } else {
    baseEach(collection, function(value, key, collection) {
      setter(result, value, iteratee(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.inject"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>inject (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.collection.inject)
- description and source-code
```javascript
inject = function (collection, iteratee, accumulator, thisArg) {
  var initFromArray = arguments.length < 3;
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee, accumulator, initFromArray)
    : baseReduce(collection, baseCallback(iteratee, thisArg, 4), accumulator, initFromArray, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.invoke"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>invoke ()](#apidoc.element.lodash-node.collection.invoke)
- description and source-code
```javascript
invoke = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.map"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>map (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.map)
- description and source-code
```javascript
function map(collection, iteratee, thisArg) {
  var func = isArray(collection) ? arrayMap : baseMap;
  iteratee = baseCallback(iteratee, thisArg, 3);
  return func(collection, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.max"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>max (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.max)
- description and source-code
```javascript
max = function (collection, iteratee, thisArg) {
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  iteratee = baseCallback(iteratee, thisArg, 3);
  if (iteratee.length == 1) {
    collection = isArray(collection) ? collection : toIterable(collection);
    var result = arrayExtremum(collection, iteratee, comparator, exValue);
    if (!(collection.length && result === exValue)) {
      return result;
    }
  }
  return baseExtremum(collection, iteratee, comparator, exValue);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.min"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>min (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.min)
- description and source-code
```javascript
min = function (collection, iteratee, thisArg) {
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  iteratee = baseCallback(iteratee, thisArg, 3);
  if (iteratee.length == 1) {
    collection = isArray(collection) ? collection : toIterable(collection);
    var result = arrayExtremum(collection, iteratee, comparator, exValue);
    if (!(collection.length && result === exValue)) {
      return result;
    }
  }
  return baseExtremum(collection, iteratee, comparator, exValue);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.partition"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>partition (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.partition)
- description and source-code
```javascript
partition = function (collection, iteratee, thisArg) {
  var result = initializer ? initializer() : {};
  iteratee = baseCallback(iteratee, thisArg, 3);

  if (isArray(collection)) {
    var index = -1,
        length = collection.length;

    while (++index < length) {
      var value = collection[index];
      setter(result, value, iteratee(value, index, collection), collection);
    }
  } else {
    baseEach(collection, function(value, key, collection) {
      setter(result, value, iteratee(value, key, collection), collection);
    });
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.pluck"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>pluck (collection, path)](#apidoc.element.lodash-node.collection.pluck)
- description and source-code
```javascript
function pluck(collection, path) {
  return map(collection, property(path));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.reduce"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>reduce (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.collection.reduce)
- description and source-code
```javascript
reduce = function (collection, iteratee, accumulator, thisArg) {
  var initFromArray = arguments.length < 3;
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee, accumulator, initFromArray)
    : baseReduce(collection, baseCallback(iteratee, thisArg, 4), accumulator, initFromArray, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.reduceRight"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>reduceRight (collection, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.collection.reduceRight)
- description and source-code
```javascript
reduceRight = function (collection, iteratee, accumulator, thisArg) {
  var initFromArray = arguments.length < 3;
  return (typeof iteratee == 'function' && thisArg === undefined && isArray(collection))
    ? arrayFunc(collection, iteratee, accumulator, initFromArray)
    : baseReduce(collection, baseCallback(iteratee, thisArg, 4), accumulator, initFromArray, eachFunc);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.reject"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>reject (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.reject)
- description and source-code
```javascript
function reject(collection, predicate, thisArg) {
  var func = isArray(collection) ? arrayFilter : baseFilter;
  predicate = baseCallback(predicate, thisArg, 3);
  return func(collection, function(value, index, collection) {
    return !predicate(value, index, collection);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.sample"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>sample (collection, n, guard)](#apidoc.element.lodash-node.collection.sample)
- description and source-code
```javascript
function sample(collection, n, guard) {
  if (guard ? isIterateeCall(collection, n, guard) : n == null) {
    collection = toIterable(collection);
    var length = collection.length;
    return length > 0 ? collection[baseRandom(0, length - 1)] : undefined;
  }
  var index = -1,
      result = toArray(collection),
      length = result.length,
      lastIndex = length - 1;

  n = nativeMin(n < 0 ? 0 : (+n || 0), length);
  while (++index < n) {
    var rand = baseRandom(index, lastIndex),
        value = result[rand];

    result[rand] = result[index];
    result[index] = value;
  }
  result.length = n;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.select"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>select (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.select)
- description and source-code
```javascript
function filter(collection, predicate, thisArg) {
  var func = isArray(collection) ? arrayFilter : baseFilter;
  predicate = baseCallback(predicate, thisArg, 3);
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.shuffle"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>shuffle (collection)](#apidoc.element.lodash-node.collection.shuffle)
- description and source-code
```javascript
function shuffle(collection) {
  return sample(collection, POSITIVE_INFINITY);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.size"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>size (collection)](#apidoc.element.lodash-node.collection.size)
- description and source-code
```javascript
function size(collection) {
  var length = collection ? getLength(collection) : 0;
  return isLength(length) ? length : keys(collection).length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.some"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>some (collection, predicate, thisArg)](#apidoc.element.lodash-node.collection.some)
- description and source-code
```javascript
function some(collection, predicate, thisArg) {
  var func = isArray(collection) ? arraySome : baseSome;
  if (thisArg && isIterateeCall(collection, predicate, thisArg)) {
    predicate = undefined;
  }
  if (typeof predicate != 'function' || thisArg !== undefined) {
    predicate = baseCallback(predicate, thisArg, 3);
  }
  return func(collection, predicate);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.sortBy"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>sortBy (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.sortBy)
- description and source-code
```javascript
function sortBy(collection, iteratee, thisArg) {
  if (collection == null) {
    return [];
  }
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  var index = -1;
  iteratee = baseCallback(iteratee, thisArg, 3);

  var result = baseMap(collection, function(value, key, collection) {
    return { 'criteria': iteratee(value, key, collection), 'index': ++index, 'value': value };
  });
  return baseSortBy(result, compareAscending);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.sortByAll"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>sortByAll ()](#apidoc.element.lodash-node.collection.sortByAll)
- description and source-code
```javascript
sortByAll = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.sortByOrder"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>sortByOrder (collection, iteratees, orders, guard)](#apidoc.element.lodash-node.collection.sortByOrder)
- description and source-code
```javascript
function sortByOrder(collection, iteratees, orders, guard) {
  if (collection == null) {
    return [];
  }
  if (guard && isIterateeCall(iteratees, orders, guard)) {
    orders = undefined;
  }
  if (!isArray(iteratees)) {
    iteratees = iteratees == null ? [] : [iteratees];
  }
  if (!isArray(orders)) {
    orders = orders == null ? [] : [orders];
  }
  return baseSortByOrder(collection, iteratees, orders);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.sum"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>sum (collection, iteratee, thisArg)](#apidoc.element.lodash-node.collection.sum)
- description and source-code
```javascript
function sum(collection, iteratee, thisArg) {
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  iteratee = baseCallback(iteratee, thisArg, 3);
  return iteratee.length == 1
    ? arraySum(isArray(collection) ? collection : toIterable(collection), iteratee)
    : baseSum(collection, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.collection.where"></a>[function <span class="apidocSignatureSpan">lodash-node.collection.</span>where (collection, source)](#apidoc.element.lodash-node.collection.where)
- description and source-code
```javascript
function where(collection, source) {
  return filter(collection, baseMatches(source));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.curry"></a>[module lodash-node.curry](#apidoc.module.lodash-node.curry)

#### <a name="apidoc.element.lodash-node.curry.curry"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>curry (func, arity, guard)](#apidoc.element.lodash-node.curry.curry)
- description and source-code
```javascript
function curryFunc(func, arity, guard) {
  if (guard && isIterateeCall(func, arity, guard)) {
    arity = undefined;
  }
  var result = createWrapper(func, flag, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = curryFunc.placeholder;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.curry.placeholder"></a>[function <span class="apidocSignatureSpan">lodash-node.curry.</span>placeholder (value)](#apidoc.element.lodash-node.curry.placeholder)
- description and source-code
```javascript
function lodash(value) {
  if (isObjectLike(value) && !isArray(value) && !(value instanceof LazyWrapper)) {
    if (value instanceof LodashWrapper) {
      return value;
    }
    if (hasOwnProperty.call(value, '__chain__') && hasOwnProperty.call(value, '__wrapped__')) {
      return wrapperClone(value);
    }
  }
  return new LodashWrapper(value);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.curryRight"></a>[module lodash-node.curryRight](#apidoc.module.lodash-node.curryRight)

#### <a name="apidoc.element.lodash-node.curryRight.curryRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>curryRight (func, arity, guard)](#apidoc.element.lodash-node.curryRight.curryRight)
- description and source-code
```javascript
function curryFunc(func, arity, guard) {
  if (guard && isIterateeCall(func, arity, guard)) {
    arity = undefined;
  }
  var result = createWrapper(func, flag, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = curryFunc.placeholder;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.curryRight.placeholder"></a>[function <span class="apidocSignatureSpan">lodash-node.curryRight.</span>placeholder (value)](#apidoc.element.lodash-node.curryRight.placeholder)
- description and source-code
```javascript
function lodash(value) {
  if (isObjectLike(value) && !isArray(value) && !(value instanceof LazyWrapper)) {
    if (value instanceof LodashWrapper) {
      return value;
    }
    if (hasOwnProperty.call(value, '__chain__') && hasOwnProperty.call(value, '__wrapped__')) {
      return wrapperClone(value);
    }
  }
  return new LodashWrapper(value);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.date"></a>[module lodash-node.date](#apidoc.module.lodash-node.date)

#### <a name="apidoc.element.lodash-node.date.now"></a>[function <span class="apidocSignatureSpan">lodash-node.date.</span>now ()](#apidoc.element.lodash-node.date.now)
- description and source-code
```javascript
function now() { [native code] }
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.function"></a>[module lodash-node.function](#apidoc.module.lodash-node.function)

#### <a name="apidoc.element.lodash-node.function.after"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>after (n, func)](#apidoc.element.lodash-node.function.after)
- description and source-code
```javascript
function after(n, func) {
  if (typeof func != 'function') {
    if (typeof n == 'function') {
      var temp = n;
      n = func;
      func = temp;
    } else {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
  }
  n = nativeIsFinite(n = +n) ? n : 0;
  return function() {
    if (--n < 1) {
      return func.apply(this, arguments);
    }
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.ary"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>ary (func, n, guard)](#apidoc.element.lodash-node.function.ary)
- description and source-code
```javascript
function ary(func, n, guard) {
  if (guard && isIterateeCall(func, n, guard)) {
    n = undefined;
  }
  n = (func && n == null) ? func.length : nativeMax(+n || 0, 0);
  return createWrapper(func, ARY_FLAG, undefined, undefined, undefined, undefined, n);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.backflow"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>backflow ()](#apidoc.element.lodash-node.function.backflow)
- description and source-code
```javascript
backflow = function () {
  var wrapper,
      length = arguments.length,
      index = fromRight ? length : -1,
      leftIndex = 0,
      funcs = Array(length);

  while ((fromRight ? index-- : ++index < length)) {
    var func = funcs[leftIndex++] = arguments[index];
    if (typeof func != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    if (!wrapper && LodashWrapper.prototype.thru && getFuncName(func) == 'wrapper') {
      wrapper = new LodashWrapper([], true);
    }
  }
  index = wrapper ? -1 : length;
  while (++index < length) {
    func = funcs[index];

    var funcName = getFuncName(func),
        data = funcName == 'wrapper' ? getData(func) : undefined;

    if (data && isLaziable(data[0]) && data[1] == (ARY_FLAG | CURRY_FLAG | PARTIAL_FLAG | REARG_FLAG) && !data[4].length && data
[9] == 1) {
      wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
    } else {
      wrapper = (func.length == 1 && isLaziable(func)) ? wrapper[funcName]() : wrapper.thru(func);
    }
  }
  return function() {
    var args = arguments,
        value = args[0];

    if (wrapper && args.length == 1 && isArray(value) && value.length >= LARGE_ARRAY_SIZE) {
      return wrapper.plant(value).value();
    }
    var index = 0,
        result = length ? funcs[index].apply(this, args) : value;

    while (++index < length) {
      result = funcs[index].call(this, result);
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.before"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>before (n, func)](#apidoc.element.lodash-node.function.before)
- description and source-code
```javascript
function before(n, func) {
  var result;
  if (typeof func != 'function') {
    if (typeof n == 'function') {
      var temp = n;
      n = func;
      func = temp;
    } else {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
  }
  return function() {
    if (--n > 0) {
      result = func.apply(this, arguments);
    }
    if (n <= 1) {
      func = undefined;
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.bind"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>bind ()](#apidoc.element.lodash-node.function.bind)
- description and source-code
```javascript
bind = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.bindAll"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>bindAll ()](#apidoc.element.lodash-node.function.bindAll)
- description and source-code
```javascript
bindAll = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.bindKey"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>bindKey ()](#apidoc.element.lodash-node.function.bindKey)
- description and source-code
```javascript
bindKey = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.compose"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>compose ()](#apidoc.element.lodash-node.function.compose)
- description and source-code
```javascript
compose = function () {
  var wrapper,
      length = arguments.length,
      index = fromRight ? length : -1,
      leftIndex = 0,
      funcs = Array(length);

  while ((fromRight ? index-- : ++index < length)) {
    var func = funcs[leftIndex++] = arguments[index];
    if (typeof func != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    if (!wrapper && LodashWrapper.prototype.thru && getFuncName(func) == 'wrapper') {
      wrapper = new LodashWrapper([], true);
    }
  }
  index = wrapper ? -1 : length;
  while (++index < length) {
    func = funcs[index];

    var funcName = getFuncName(func),
        data = funcName == 'wrapper' ? getData(func) : undefined;

    if (data && isLaziable(data[0]) && data[1] == (ARY_FLAG | CURRY_FLAG | PARTIAL_FLAG | REARG_FLAG) && !data[4].length && data
[9] == 1) {
      wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
    } else {
      wrapper = (func.length == 1 && isLaziable(func)) ? wrapper[funcName]() : wrapper.thru(func);
    }
  }
  return function() {
    var args = arguments,
        value = args[0];

    if (wrapper && args.length == 1 && isArray(value) && value.length >= LARGE_ARRAY_SIZE) {
      return wrapper.plant(value).value();
    }
    var index = 0,
        result = length ? funcs[index].apply(this, args) : value;

    while (++index < length) {
      result = funcs[index].call(this, result);
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.curry"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>curry (func, arity, guard)](#apidoc.element.lodash-node.function.curry)
- description and source-code
```javascript
function curryFunc(func, arity, guard) {
  if (guard && isIterateeCall(func, arity, guard)) {
    arity = undefined;
  }
  var result = createWrapper(func, flag, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = curryFunc.placeholder;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.curryRight"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>curryRight (func, arity, guard)](#apidoc.element.lodash-node.function.curryRight)
- description and source-code
```javascript
function curryFunc(func, arity, guard) {
  if (guard && isIterateeCall(func, arity, guard)) {
    arity = undefined;
  }
  var result = createWrapper(func, flag, undefined, undefined, undefined, undefined, undefined, arity);
  result.placeholder = curryFunc.placeholder;
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.debounce"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>debounce (func, wait, options)](#apidoc.element.lodash-node.function.debounce)
- description and source-code
```javascript
function debounce(func, wait, options) {
  var args,
      maxTimeoutId,
      result,
      stamp,
      thisArg,
      timeoutId,
      trailingCall,
      lastCalled = 0,
      maxWait = false,
      trailing = true;

  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  wait = wait < 0 ? 0 : (+wait || 0);
  if (options === true) {
    var leading = true;
    trailing = false;
  } else if (isObject(options)) {
    leading = !!options.leading;
    maxWait = 'maxWait' in options && nativeMax(+options.maxWait || 0, wait);
    trailing = 'trailing' in options ? !!options.trailing : trailing;
  }

  function cancel() {
    if (timeoutId) {
      clearTimeout(timeoutId);
    }
    if (maxTimeoutId) {
      clearTimeout(maxTimeoutId);
    }
    lastCalled = 0;
    maxTimeoutId = timeoutId = trailingCall = undefined;
  }

  function complete(isCalled, id) {
    if (id) {
      clearTimeout(id);
    }
    maxTimeoutId = timeoutId = trailingCall = undefined;
    if (isCalled) {
      lastCalled = now();
      result = func.apply(thisArg, args);
      if (!timeoutId && !maxTimeoutId) {
        args = thisArg = undefined;
      }
    }
  }

  function delayed() {
    var remaining = wait - (now() - stamp);
    if (remaining <= 0 || remaining > wait) {
      complete(trailingCall, maxTimeoutId);
    } else {
      timeoutId = setTimeout(delayed, remaining);
    }
  }

  function maxDelayed() {
    complete(trailing, timeoutId);
  }

  function debounced() {
    args = arguments;
    stamp = now();
    thisArg = this;
    trailingCall = trailing && (timeoutId || !leading);

    if (maxWait === false) {
      var leadingCall = leading && !timeoutId;
    } else {
      if (!maxTimeoutId && !leading) {
        lastCalled = stamp;
      }
      var remaining = maxWait - (stamp - lastCalled),
          isCalled = remaining <= 0 || remaining > maxWait;

      if (isCalled) {
        if (maxTimeoutId) {
          maxTimeoutId = clearTimeout(maxTimeoutId);
        }
        lastCalled = stamp;
        result = func.apply(thisArg, args);
      }
      else if (!maxTimeoutId) {
        maxTimeoutId = setTimeout(maxDelayed, remaining);
      }
    }
    if (isCalled && timeoutId) {
      timeoutId = clearTimeout(timeoutId);
    }
    else if (!timeoutId && wait !== maxWait) {
      timeoutId = setTimeout(delayed, wait);
    }
    if (leadingCall) {
      isCalled = true;
      result = func.apply(thisArg, args);
    }
    if (isCalled && !timeoutId && !maxTimeoutId) {
      args = thisArg = undefined;
    }
    return result;
  }
  debounced.cancel = cancel;
  return debounced;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.defer"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>defer ()](#apidoc.element.lodash-node.function.defer)
- description and source-code
```javascript
defer = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.delay"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>delay ()](#apidoc.element.lodash-node.function.delay)
- description and source-code
```javascript
delay = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.flow"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>flow ()](#apidoc.element.lodash-node.function.flow)
- description and source-code
```javascript
flow = function () {
  var wrapper,
      length = arguments.length,
      index = fromRight ? length : -1,
      leftIndex = 0,
      funcs = Array(length);

  while ((fromRight ? index-- : ++index < length)) {
    var func = funcs[leftIndex++] = arguments[index];
    if (typeof func != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    if (!wrapper && LodashWrapper.prototype.thru && getFuncName(func) == 'wrapper') {
      wrapper = new LodashWrapper([], true);
    }
  }
  index = wrapper ? -1 : length;
  while (++index < length) {
    func = funcs[index];

    var funcName = getFuncName(func),
        data = funcName == 'wrapper' ? getData(func) : undefined;

    if (data && isLaziable(data[0]) && data[1] == (ARY_FLAG | CURRY_FLAG | PARTIAL_FLAG | REARG_FLAG) && !data[4].length && data
[9] == 1) {
      wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
    } else {
      wrapper = (func.length == 1 && isLaziable(func)) ? wrapper[funcName]() : wrapper.thru(func);
    }
  }
  return function() {
    var args = arguments,
        value = args[0];

    if (wrapper && args.length == 1 && isArray(value) && value.length >= LARGE_ARRAY_SIZE) {
      return wrapper.plant(value).value();
    }
    var index = 0,
        result = length ? funcs[index].apply(this, args) : value;

    while (++index < length) {
      result = funcs[index].call(this, result);
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.flowRight"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>flowRight ()](#apidoc.element.lodash-node.function.flowRight)
- description and source-code
```javascript
flowRight = function () {
  var wrapper,
      length = arguments.length,
      index = fromRight ? length : -1,
      leftIndex = 0,
      funcs = Array(length);

  while ((fromRight ? index-- : ++index < length)) {
    var func = funcs[leftIndex++] = arguments[index];
    if (typeof func != 'function') {
      throw new TypeError(FUNC_ERROR_TEXT);
    }
    if (!wrapper && LodashWrapper.prototype.thru && getFuncName(func) == 'wrapper') {
      wrapper = new LodashWrapper([], true);
    }
  }
  index = wrapper ? -1 : length;
  while (++index < length) {
    func = funcs[index];

    var funcName = getFuncName(func),
        data = funcName == 'wrapper' ? getData(func) : undefined;

    if (data && isLaziable(data[0]) && data[1] == (ARY_FLAG | CURRY_FLAG | PARTIAL_FLAG | REARG_FLAG) && !data[4].length && data
[9] == 1) {
      wrapper = wrapper[getFuncName(data[0])].apply(wrapper, data[3]);
    } else {
      wrapper = (func.length == 1 && isLaziable(func)) ? wrapper[funcName]() : wrapper.thru(func);
    }
  }
  return function() {
    var args = arguments,
        value = args[0];

    if (wrapper && args.length == 1 && isArray(value) && value.length >= LARGE_ARRAY_SIZE) {
      return wrapper.plant(value).value();
    }
    var index = 0,
        result = length ? funcs[index].apply(this, args) : value;

    while (++index < length) {
      result = funcs[index].call(this, result);
    }
    return result;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.memoize"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>memoize (func, resolver)](#apidoc.element.lodash-node.function.memoize)
- description and source-code
```javascript
function memoize(func, resolver) {
  if (typeof func != 'function' || (resolver && typeof resolver != 'function')) {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  var memoized = function() {
    var args = arguments,
        key = resolver ? resolver.apply(this, args) : args[0],
        cache = memoized.cache;

    if (cache.has(key)) {
      return cache.get(key);
    }
    var result = func.apply(this, args);
    memoized.cache = cache.set(key, result);
    return result;
  };
  memoized.cache = new memoize.Cache;
  return memoized;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.modArgs"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>modArgs ()](#apidoc.element.lodash-node.function.modArgs)
- description and source-code
```javascript
modArgs = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.negate"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>negate (predicate)](#apidoc.element.lodash-node.function.negate)
- description and source-code
```javascript
function negate(predicate) {
  if (typeof predicate != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  return function() {
    return !predicate.apply(this, arguments);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.once"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>once (func)](#apidoc.element.lodash-node.function.once)
- description and source-code
```javascript
function once(func) {
  return before(2, func);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.partial"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>partial ()](#apidoc.element.lodash-node.function.partial)
- description and source-code
```javascript
partial = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.partialRight"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>partialRight ()](#apidoc.element.lodash-node.function.partialRight)
- description and source-code
```javascript
partialRight = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.rearg"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>rearg ()](#apidoc.element.lodash-node.function.rearg)
- description and source-code
```javascript
rearg = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.restParam"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>restParam (func, start)](#apidoc.element.lodash-node.function.restParam)
- description and source-code
```javascript
function restParam(func, start) {
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  start = nativeMax(start === undefined ? (func.length - 1) : (+start || 0), 0);
  return function() {
    var args = arguments,
        index = -1,
        length = nativeMax(args.length - start, 0),
        rest = Array(length);

    while (++index < length) {
      rest[index] = args[start + index];
    }
    switch (start) {
      case 0: return func.call(this, rest);
      case 1: return func.call(this, args[0], rest);
      case 2: return func.call(this, args[0], args[1], rest);
    }
    var otherArgs = Array(start + 1);
    index = -1;
    while (++index < start) {
      otherArgs[index] = args[index];
    }
    otherArgs[start] = rest;
    return func.apply(this, otherArgs);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.spread"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>spread (func)](#apidoc.element.lodash-node.function.spread)
- description and source-code
```javascript
function spread(func) {
  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  return function(array) {
    return func.apply(this, array);
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.throttle"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>throttle (func, wait, options)](#apidoc.element.lodash-node.function.throttle)
- description and source-code
```javascript
function throttle(func, wait, options) {
  var leading = true,
      trailing = true;

  if (typeof func != 'function') {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  if (options === false) {
    leading = false;
  } else if (isObject(options)) {
    leading = 'leading' in options ? !!options.leading : leading;
    trailing = 'trailing' in options ? !!options.trailing : trailing;
  }
  return debounce(func, wait, { 'leading': leading, 'maxWait': +wait, 'trailing': trailing });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.function.wrap"></a>[function <span class="apidocSignatureSpan">lodash-node.function.</span>wrap (value, wrapper)](#apidoc.element.lodash-node.function.wrap)
- description and source-code
```javascript
function wrap(value, wrapper) {
  wrapper = wrapper == null ? identity : wrapper;
  return createWrapper(wrapper, PARTIAL_FLAG, undefined, [value], []);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.lang"></a>[module lodash-node.lang](#apidoc.module.lodash-node.lang)

#### <a name="apidoc.element.lodash-node.lang.clone"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>clone (value, isDeep, customizer, thisArg)](#apidoc.element.lodash-node.lang.clone)
- description and source-code
```javascript
function clone(value, isDeep, customizer, thisArg) {
  if (isDeep && typeof isDeep != 'boolean' && isIterateeCall(value, isDeep, customizer)) {
    isDeep = false;
  }
  else if (typeof isDeep == 'function') {
    thisArg = customizer;
    customizer = isDeep;
    isDeep = false;
  }
  return typeof customizer == 'function'
    ? baseClone(value, isDeep, bindCallback(customizer, thisArg, 3))
    : baseClone(value, isDeep);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.cloneDeep"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>cloneDeep (value, customizer, thisArg)](#apidoc.element.lodash-node.lang.cloneDeep)
- description and source-code
```javascript
function cloneDeep(value, customizer, thisArg) {
  return typeof customizer == 'function'
    ? baseClone(value, true, bindCallback(customizer, thisArg, 3))
    : baseClone(value, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.eq"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>eq (value, other, customizer, thisArg)](#apidoc.element.lodash-node.lang.eq)
- description and source-code
```javascript
function isEqual(value, other, customizer, thisArg) {
  customizer = typeof customizer == 'function' ? bindCallback(customizer, thisArg, 3) : undefined;
  var result = customizer ? customizer(value, other) : undefined;
  return  result === undefined ? baseIsEqual(value, other, customizer) : !!result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.gt"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>gt (value, other)](#apidoc.element.lodash-node.lang.gt)
- description and source-code
```javascript
function gt(value, other) {
  return value > other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.gte"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>gte (value, other)](#apidoc.element.lodash-node.lang.gte)
- description and source-code
```javascript
function gte(value, other) {
  return value >= other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isArguments"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isArguments (value)](#apidoc.element.lodash-node.lang.isArguments)
- description and source-code
```javascript
function isArguments(value) {
  return isObjectLike(value) && isArrayLike(value) &&
    hasOwnProperty.call(value, 'callee') && !propertyIsEnumerable.call(value, 'callee');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isArray"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isArray ()](#apidoc.element.lodash-node.lang.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isBoolean"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isBoolean (value)](#apidoc.element.lodash-node.lang.isBoolean)
- description and source-code
```javascript
function isBoolean(value) {
  return value === true || value === false || (isObjectLike(value) && objToString.call(value) == boolTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isDate"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isDate (value)](#apidoc.element.lodash-node.lang.isDate)
- description and source-code
```javascript
function isDate(value) {
  return isObjectLike(value) && objToString.call(value) == dateTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isElement"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isElement (value)](#apidoc.element.lodash-node.lang.isElement)
- description and source-code
```javascript
function isElement(value) {
  return !!value && value.nodeType === 1 && isObjectLike(value) && !isPlainObject(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isEmpty"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isEmpty (value)](#apidoc.element.lodash-node.lang.isEmpty)
- description and source-code
```javascript
function isEmpty(value) {
  if (value == null) {
    return true;
  }
  if (isArrayLike(value) && (isArray(value) || isString(value) || isArguments(value) ||
      (isObjectLike(value) && isFunction(value.splice)))) {
    return !value.length;
  }
  return !keys(value).length;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isEqual"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isEqual (value, other, customizer, thisArg)](#apidoc.element.lodash-node.lang.isEqual)
- description and source-code
```javascript
function isEqual(value, other, customizer, thisArg) {
  customizer = typeof customizer == 'function' ? bindCallback(customizer, thisArg, 3) : undefined;
  var result = customizer ? customizer(value, other) : undefined;
  return  result === undefined ? baseIsEqual(value, other, customizer) : !!result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isError"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isError (value)](#apidoc.element.lodash-node.lang.isError)
- description and source-code
```javascript
function isError(value) {
  return isObjectLike(value) && typeof value.message == 'string' && objToString.call(value) == errorTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isFinite"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isFinite (value)](#apidoc.element.lodash-node.lang.isFinite)
- description and source-code
```javascript
function isFinite(value) {
  return typeof value == 'number' && nativeIsFinite(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isFunction"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isFunction (value)](#apidoc.element.lodash-node.lang.isFunction)
- description and source-code
```javascript
function isFunction(value) {
  // The use of 'Object#toString' avoids issues with the 'typeof' operator
  // in older versions of Chrome and Safari which return 'function' for regexes
  // and Safari 8 which returns 'object' for typed array constructors.
  return isObject(value) && objToString.call(value) == funcTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isMatch"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isMatch (object, source, customizer, thisArg)](#apidoc.element.lodash-node.lang.isMatch)
- description and source-code
```javascript
function isMatch(object, source, customizer, thisArg) {
  customizer = typeof customizer == 'function' ? bindCallback(customizer, thisArg, 3) : undefined;
  return baseIsMatch(object, getMatchData(source), customizer);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isNaN"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isNaN (value)](#apidoc.element.lodash-node.lang.isNaN)
- description and source-code
```javascript
function isNaN(value) {
  // An 'NaN' primitive is the only value that is not equal to itself.
  // Perform the 'toStringTag' check first to avoid errors with some host objects in IE.
  return isNumber(value) && value != +value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isNative"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isNative (value)](#apidoc.element.lodash-node.lang.isNative)
- description and source-code
```javascript
function isNative(value) {
  if (value == null) {
    return false;
  }
  if (isFunction(value)) {
    return reIsNative.test(fnToString.call(value));
  }
  return isObjectLike(value) && (isHostObject(value) ? reIsNative : reIsHostCtor).test(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isNull"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isNull (value)](#apidoc.element.lodash-node.lang.isNull)
- description and source-code
```javascript
function isNull(value) {
  return value === null;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isNumber"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isNumber (value)](#apidoc.element.lodash-node.lang.isNumber)
- description and source-code
```javascript
function isNumber(value) {
  return typeof value == 'number' || (isObjectLike(value) && objToString.call(value) == numberTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isObject"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isObject (value)](#apidoc.element.lodash-node.lang.isObject)
- description and source-code
```javascript
function isObject(value) {
  // Avoid a V8 JIT bug in Chrome 19-20.
  // See https://code.google.com/p/v8/issues/detail?id=2291 for more details.
  var type = typeof value;
  return !!value && (type == 'object' || type == 'function');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isPlainObject"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isPlainObject (value)](#apidoc.element.lodash-node.lang.isPlainObject)
- description and source-code
```javascript
function isPlainObject(value) {
  var Ctor;

  // Exit early for non 'Object' objects.
  if (!(isObjectLike(value) && objToString.call(value) == objectTag && !isHostObject(value) && !isArguments(value)) ||
      (!hasOwnProperty.call(value, 'constructor') && (Ctor = value.constructor, typeof Ctor == 'function' && !(Ctor instanceof Ctor
)))) {
    return false;
  }
  // IE < 9 iterates inherited properties before own properties. If the first
  // iterated property is an object's own property then there are no inherited
  // enumerable properties.
  var result;
  if (support.ownLast) {
    baseForIn(value, function(subValue, key, object) {
      result = hasOwnProperty.call(object, key);
      return false;
    });
    return result !== false;
  }
  // In most environments an object's own properties are iterated before
  // its inherited properties. If the last iterated property is an object's
  // own property then there are no inherited enumerable properties.
  baseForIn(value, function(subValue, key) {
    result = key;
  });
  return result === undefined || hasOwnProperty.call(value, result);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isRegExp"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isRegExp (value)](#apidoc.element.lodash-node.lang.isRegExp)
- description and source-code
```javascript
function isRegExp(value) {
  return isObject(value) && objToString.call(value) == regexpTag;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isString"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isString (value)](#apidoc.element.lodash-node.lang.isString)
- description and source-code
```javascript
function isString(value) {
  return typeof value == 'string' || (isObjectLike(value) && objToString.call(value) == stringTag);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isTypedArray"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isTypedArray (value)](#apidoc.element.lodash-node.lang.isTypedArray)
- description and source-code
```javascript
function isTypedArray(value) {
  return isObjectLike(value) && isLength(value.length) && !!typedArrayTags[objToString.call(value)];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.isUndefined"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>isUndefined (value)](#apidoc.element.lodash-node.lang.isUndefined)
- description and source-code
```javascript
function isUndefined(value) {
  return value === undefined;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.lt"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>lt (value, other)](#apidoc.element.lodash-node.lang.lt)
- description and source-code
```javascript
function lt(value, other) {
  return value < other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.lte"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>lte (value, other)](#apidoc.element.lodash-node.lang.lte)
- description and source-code
```javascript
function lte(value, other) {
  return value <= other;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.toArray"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>toArray (value)](#apidoc.element.lodash-node.lang.toArray)
- description and source-code
```javascript
function toArray(value) {
  var length = value ? getLength(value) : 0;
  if (!isLength(length)) {
    return values(value);
  }
  if (!length) {
    return [];
  }
  return (support.unindexedChars && isString(value))
    ? value.split('')
    : arrayCopy(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.lang.toPlainObject"></a>[function <span class="apidocSignatureSpan">lodash-node.lang.</span>toPlainObject (value)](#apidoc.element.lodash-node.lang.toPlainObject)
- description and source-code
```javascript
function toPlainObject(value) {
  return baseCopy(value, keysIn(value));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.math"></a>[module lodash-node.math](#apidoc.module.lodash-node.math)

#### <a name="apidoc.element.lodash-node.math.add"></a>[function <span class="apidocSignatureSpan">lodash-node.math.</span>add (augend, addend)](#apidoc.element.lodash-node.math.add)
- description and source-code
```javascript
function add(augend, addend) {
  return (+augend || 0) + (+addend || 0);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.math.ceil"></a>[function <span class="apidocSignatureSpan">lodash-node.math.</span>ceil (number, precision)](#apidoc.element.lodash-node.math.ceil)
- description and source-code
```javascript
ceil = function (number, precision) {
  precision = precision === undefined ? 0 : (+precision || 0);
  if (precision) {
    precision = pow(10, precision);
    return func(number * precision) / precision;
  }
  return func(number);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.math.floor"></a>[function <span class="apidocSignatureSpan">lodash-node.math.</span>floor (number, precision)](#apidoc.element.lodash-node.math.floor)
- description and source-code
```javascript
floor = function (number, precision) {
  precision = precision === undefined ? 0 : (+precision || 0);
  if (precision) {
    precision = pow(10, precision);
    return func(number * precision) / precision;
  }
  return func(number);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.math.max"></a>[function <span class="apidocSignatureSpan">lodash-node.math.</span>max (collection, iteratee, thisArg)](#apidoc.element.lodash-node.math.max)
- description and source-code
```javascript
max = function (collection, iteratee, thisArg) {
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  iteratee = baseCallback(iteratee, thisArg, 3);
  if (iteratee.length == 1) {
    collection = isArray(collection) ? collection : toIterable(collection);
    var result = arrayExtremum(collection, iteratee, comparator, exValue);
    if (!(collection.length && result === exValue)) {
      return result;
    }
  }
  return baseExtremum(collection, iteratee, comparator, exValue);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.math.min"></a>[function <span class="apidocSignatureSpan">lodash-node.math.</span>min (collection, iteratee, thisArg)](#apidoc.element.lodash-node.math.min)
- description and source-code
```javascript
min = function (collection, iteratee, thisArg) {
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  iteratee = baseCallback(iteratee, thisArg, 3);
  if (iteratee.length == 1) {
    collection = isArray(collection) ? collection : toIterable(collection);
    var result = arrayExtremum(collection, iteratee, comparator, exValue);
    if (!(collection.length && result === exValue)) {
      return result;
    }
  }
  return baseExtremum(collection, iteratee, comparator, exValue);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.math.round"></a>[function <span class="apidocSignatureSpan">lodash-node.math.</span>round (number, precision)](#apidoc.element.lodash-node.math.round)
- description and source-code
```javascript
round = function (number, precision) {
  precision = precision === undefined ? 0 : (+precision || 0);
  if (precision) {
    precision = pow(10, precision);
    return func(number * precision) / precision;
  }
  return func(number);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.math.sum"></a>[function <span class="apidocSignatureSpan">lodash-node.math.</span>sum (collection, iteratee, thisArg)](#apidoc.element.lodash-node.math.sum)
- description and source-code
```javascript
function sum(collection, iteratee, thisArg) {
  if (thisArg && isIterateeCall(collection, iteratee, thisArg)) {
    iteratee = undefined;
  }
  iteratee = baseCallback(iteratee, thisArg, 3);
  return iteratee.length == 1
    ? arraySum(isArray(collection) ? collection : toIterable(collection), iteratee)
    : baseSum(collection, iteratee);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.memoize"></a>[module lodash-node.memoize](#apidoc.module.lodash-node.memoize)

#### <a name="apidoc.element.lodash-node.memoize.memoize"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>memoize (func, resolver)](#apidoc.element.lodash-node.memoize.memoize)
- description and source-code
```javascript
function memoize(func, resolver) {
  if (typeof func != 'function' || (resolver && typeof resolver != 'function')) {
    throw new TypeError(FUNC_ERROR_TEXT);
  }
  var memoized = function() {
    var args = arguments,
        key = resolver ? resolver.apply(this, args) : args[0],
        cache = memoized.cache;

    if (cache.has(key)) {
      return cache.get(key);
    }
    var result = func.apply(this, args);
    memoized.cache = cache.set(key, result);
    return result;
  };
  memoized.cache = new memoize.Cache;
  return memoized;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.memoize.Cache"></a>[function <span class="apidocSignatureSpan">lodash-node.memoize.</span>Cache ()](#apidoc.element.lodash-node.memoize.Cache)
- description and source-code
```javascript
function MapCache() {
  this.__data__ = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.memoize.Cache"></a>[module lodash-node.memoize.Cache](#apidoc.module.lodash-node.memoize.Cache)

#### <a name="apidoc.element.lodash-node.memoize.Cache.Cache"></a>[function <span class="apidocSignatureSpan">lodash-node.memoize.</span>Cache ()](#apidoc.element.lodash-node.memoize.Cache.Cache)
- description and source-code
```javascript
function MapCache() {
  this.__data__ = {};
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.memoize.Cache.prototype"></a>[module lodash-node.memoize.Cache.prototype](#apidoc.module.lodash-node.memoize.Cache.prototype)

#### <a name="apidoc.element.lodash-node.memoize.Cache.prototype.delete"></a>[function <span class="apidocSignatureSpan">lodash-node.memoize.Cache.prototype.</span>delete (key)](#apidoc.element.lodash-node.memoize.Cache.prototype.delete)
- description and source-code
```javascript
function mapDelete(key) {
  return this.has(key) && delete this.__data__[key];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.memoize.Cache.prototype.get"></a>[function <span class="apidocSignatureSpan">lodash-node.memoize.Cache.prototype.</span>get (key)](#apidoc.element.lodash-node.memoize.Cache.prototype.get)
- description and source-code
```javascript
function mapGet(key) {
  return key == '__proto__' ? undefined : this.__data__[key];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.memoize.Cache.prototype.has"></a>[function <span class="apidocSignatureSpan">lodash-node.memoize.Cache.prototype.</span>has (key)](#apidoc.element.lodash-node.memoize.Cache.prototype.has)
- description and source-code
```javascript
function mapHas(key) {
  return key != '__proto__' && hasOwnProperty.call(this.__data__, key);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.memoize.Cache.prototype.set"></a>[function <span class="apidocSignatureSpan">lodash-node.memoize.Cache.prototype.</span>set (key, value)](#apidoc.element.lodash-node.memoize.Cache.prototype.set)
- description and source-code
```javascript
function mapSet(key, value) {
  if (key != '__proto__') {
    this.__data__[key] = value;
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.number"></a>[module lodash-node.number](#apidoc.module.lodash-node.number)

#### <a name="apidoc.element.lodash-node.number.inRange"></a>[function <span class="apidocSignatureSpan">lodash-node.number.</span>inRange (value, start, end)](#apidoc.element.lodash-node.number.inRange)
- description and source-code
```javascript
function inRange(value, start, end) {
  start = +start || 0;
  if (end === undefined) {
    end = start;
    start = 0;
  } else {
    end = +end || 0;
  }
  return value >= nativeMin(start, end) && value < nativeMax(start, end);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.number.random"></a>[function <span class="apidocSignatureSpan">lodash-node.number.</span>random (min, max, floating)](#apidoc.element.lodash-node.number.random)
- description and source-code
```javascript
function random(min, max, floating) {
  if (floating && isIterateeCall(min, max, floating)) {
    max = floating = undefined;
  }
  var noMin = min == null,
      noMax = max == null;

  if (floating == null) {
    if (noMax && typeof min == 'boolean') {
      floating = min;
      min = 1;
    }
    else if (typeof max == 'boolean') {
      floating = max;
      noMax = true;
    }
  }
  if (noMin && noMax) {
    max = 1;
    noMax = false;
  }
  min = +min || 0;
  if (noMax) {
    max = min;
    min = 0;
  } else {
    max = +max || 0;
  }
  if (floating || min % 1 || max % 1) {
    var rand = nativeRandom();
    return nativeMin(min + (rand * (max - min + parseFloat('1e-' + ((rand + '').length - 1)))), max);
  }
  return baseRandom(min, max);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.object"></a>[module lodash-node.object](#apidoc.module.lodash-node.object)

#### <a name="apidoc.element.lodash-node.object.assign"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>assign ()](#apidoc.element.lodash-node.object.assign)
- description and source-code
```javascript
assign = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.create"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>create (prototype, properties, guard)](#apidoc.element.lodash-node.object.create)
- description and source-code
```javascript
function create(prototype, properties, guard) {
  var result = baseCreate(prototype);
  if (guard && isIterateeCall(prototype, properties, guard)) {
    properties = undefined;
  }
  return properties ? baseAssign(result, properties) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.defaults"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>defaults ()](#apidoc.element.lodash-node.object.defaults)
- description and source-code
```javascript
defaults = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.defaultsDeep"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>defaultsDeep ()](#apidoc.element.lodash-node.object.defaultsDeep)
- description and source-code
```javascript
defaultsDeep = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.extend"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>extend ()](#apidoc.element.lodash-node.object.extend)
- description and source-code
```javascript
extend = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.findKey"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>findKey (object, predicate, thisArg)](#apidoc.element.lodash-node.object.findKey)
- description and source-code
```javascript
findKey = function (object, predicate, thisArg) {
  predicate = baseCallback(predicate, thisArg, 3);
  return baseFind(object, predicate, objectFunc, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.findLastKey"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>findLastKey (object, predicate, thisArg)](#apidoc.element.lodash-node.object.findLastKey)
- description and source-code
```javascript
findLastKey = function (object, predicate, thisArg) {
  predicate = baseCallback(predicate, thisArg, 3);
  return baseFind(object, predicate, objectFunc, true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.forIn"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>forIn (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.forIn)
- description and source-code
```javascript
forIn = function (object, iteratee, thisArg) {
  if (typeof iteratee != 'function' || thisArg !== undefined) {
    iteratee = bindCallback(iteratee, thisArg, 3);
  }
  return objectFunc(object, iteratee, keysIn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.forInRight"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>forInRight (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.forInRight)
- description and source-code
```javascript
forInRight = function (object, iteratee, thisArg) {
  if (typeof iteratee != 'function' || thisArg !== undefined) {
    iteratee = bindCallback(iteratee, thisArg, 3);
  }
  return objectFunc(object, iteratee, keysIn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.forOwn"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>forOwn (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.forOwn)
- description and source-code
```javascript
forOwn = function (object, iteratee, thisArg) {
  if (typeof iteratee != 'function' || thisArg !== undefined) {
    iteratee = bindCallback(iteratee, thisArg, 3);
  }
  return objectFunc(object, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.forOwnRight"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>forOwnRight (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.forOwnRight)
- description and source-code
```javascript
forOwnRight = function (object, iteratee, thisArg) {
  if (typeof iteratee != 'function' || thisArg !== undefined) {
    iteratee = bindCallback(iteratee, thisArg, 3);
  }
  return objectFunc(object, iteratee);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.functions"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>functions (object)](#apidoc.element.lodash-node.object.functions)
- description and source-code
```javascript
function functions(object) {
  return baseFunctions(object, keysIn(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.get"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>get (object, path, defaultValue)](#apidoc.element.lodash-node.object.get)
- description and source-code
```javascript
function get(object, path, defaultValue) {
  var result = object == null ? undefined : baseGet(object, toPath(path), (path + ''));
  return result === undefined ? defaultValue : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.has"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>has (object, path)](#apidoc.element.lodash-node.object.has)
- description and source-code
```javascript
function has(object, path) {
  if (object == null) {
    return false;
  }
  var result = hasOwnProperty.call(object, path);
  if (!result && !isKey(path)) {
    path = toPath(path);
    object = path.length == 1 ? object : baseGet(object, baseSlice(path, 0, -1));
    if (object == null) {
      return false;
    }
    path = last(path);
    result = hasOwnProperty.call(object, path);
  }
  return result || (isLength(object.length) && isIndex(path, object.length) &&
    (isArray(object) || isArguments(object) || isString(object)));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.invert"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>invert (object, multiValue, guard)](#apidoc.element.lodash-node.object.invert)
- description and source-code
```javascript
function invert(object, multiValue, guard) {
  if (guard && isIterateeCall(object, multiValue, guard)) {
    multiValue = undefined;
  }
  var index = -1,
      props = keys(object),
      length = props.length,
      result = {};

  while (++index < length) {
    var key = props[index],
        value = object[key];

    if (multiValue) {
      if (hasOwnProperty.call(result, value)) {
        result[value].push(key);
      } else {
        result[value] = [key];
      }
    }
    else {
      result[value] = key;
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.keys"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>keys (object)](#apidoc.element.lodash-node.object.keys)
- description and source-code
```javascript
keys = function (object) {
  var Ctor = object == null ? undefined : object.constructor;
  if ((typeof Ctor == 'function' && Ctor.prototype === object) ||
      (typeof object == 'function' ? support.enumPrototypes : isArrayLike(object))) {
    return shimKeys(object);
  }
  return isObject(object) ? nativeKeys(object) : [];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.keysIn"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>keysIn (object)](#apidoc.element.lodash-node.object.keysIn)
- description and source-code
```javascript
function keysIn(object) {
  if (object == null) {
    return [];
  }
  if (!isObject(object)) {
    object = Object(object);
  }
  var length = object.length;

  length = (length && isLength(length) &&
    (isArray(object) || isArguments(object) || isString(object)) && length) || 0;

  var Ctor = object.constructor,
      index = -1,
      proto = (isFunction(Ctor) && Ctor.prototype) || objectProto,
      isProto = proto === object,
      result = Array(length),
      skipIndexes = length > 0,
      skipErrorProps = support.enumErrorProps && (object === errorProto || object instanceof Error),
      skipProto = support.enumPrototypes && isFunction(object);

  while (++index < length) {
    result[index] = (index + '');
  }
  // lodash skips the 'constructor' property when it infers it's iterating
  // over a 'prototype' object because IE < 9 can't set the '[[Enumerable]]'
  // attribute of an existing property and the 'constructor' property of a
  // prototype defaults to non-enumerable.
  for (var key in object) {
    if (!(skipProto && key == 'prototype') &&
        !(skipErrorProps && (key == 'message' || key == 'name')) &&
        !(skipIndexes && isIndex(key, length)) &&
        !(key == 'constructor' && (isProto || !hasOwnProperty.call(object, key)))) {
      result.push(key);
    }
  }
  if (support.nonEnumShadows && object !== objectProto) {
    var tag = object === stringProto ? stringTag : (object === errorProto ? errorTag : objToString.call(object)),
        nonEnums = nonEnumProps[tag] || nonEnumProps[objectTag];

    if (tag == objectTag) {
      proto = objectProto;
    }
    length = shadowProps.length;
    while (length--) {
      key = shadowProps[length];
      var nonEnum = nonEnums[key];
      if (!(isProto && nonEnum) &&
          (nonEnum ? hasOwnProperty.call(object, key) : object[key] !== proto[key])) {
        result.push(key);
      }
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.mapKeys"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>mapKeys (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.mapKeys)
- description and source-code
```javascript
mapKeys = function (object, iteratee, thisArg) {
  var result = {};
  iteratee = baseCallback(iteratee, thisArg, 3);

  baseForOwn(object, function(value, key, object) {
    var mapped = iteratee(value, key, object);
    key = isMapKeys ? mapped : key;
    value = isMapKeys ? value : mapped;
    result[key] = value;
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.mapValues"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>mapValues (object, iteratee, thisArg)](#apidoc.element.lodash-node.object.mapValues)
- description and source-code
```javascript
mapValues = function (object, iteratee, thisArg) {
  var result = {};
  iteratee = baseCallback(iteratee, thisArg, 3);

  baseForOwn(object, function(value, key, object) {
    var mapped = iteratee(value, key, object);
    key = isMapKeys ? mapped : key;
    value = isMapKeys ? value : mapped;
    result[key] = value;
  });
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.merge"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>merge ()](#apidoc.element.lodash-node.object.merge)
- description and source-code
```javascript
merge = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.methods"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>methods (object)](#apidoc.element.lodash-node.object.methods)
- description and source-code
```javascript
function functions(object) {
  return baseFunctions(object, keysIn(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.omit"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>omit ()](#apidoc.element.lodash-node.object.omit)
- description and source-code
```javascript
omit = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.pairs"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>pairs (object)](#apidoc.element.lodash-node.object.pairs)
- description and source-code
```javascript
function pairs(object) {
  object = toObject(object);

  var index = -1,
      props = keys(object),
      length = props.length,
      result = Array(length);

  while (++index < length) {
    var key = props[index];
    result[index] = [key, object[key]];
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.pick"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>pick ()](#apidoc.element.lodash-node.object.pick)
- description and source-code
```javascript
pick = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.result"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>result (object, path, defaultValue)](#apidoc.element.lodash-node.object.result)
- description and source-code
```javascript
function result(object, path, defaultValue) {
  var result = object == null ? undefined : toObject(object)[path];
  if (result === undefined) {
    if (object != null && !isKey(path, object)) {
      path = toPath(path);
      object = path.length == 1 ? object : baseGet(object, baseSlice(path, 0, -1));
      result = object == null ? undefined : toObject(object)[last(path)];
    }
    result = result === undefined ? defaultValue : result;
  }
  return isFunction(result) ? result.call(object) : result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.set"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>set (object, path, value)](#apidoc.element.lodash-node.object.set)
- description and source-code
```javascript
function set(object, path, value) {
  if (object == null) {
    return object;
  }
  var pathKey = (path + '');
  path = (object[pathKey] != null || isKey(path, object)) ? [pathKey] : toPath(path);

  var index = -1,
      length = path.length,
      lastIndex = length - 1,
      nested = object;

  while (nested != null && ++index < length) {
    var key = path[index];
    if (isObject(nested)) {
      if (index == lastIndex) {
        nested[key] = value;
      } else if (nested[key] == null) {
        nested[key] = isIndex(path[index + 1]) ? [] : {};
      }
    }
    nested = nested[key];
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.transform"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>transform (object, iteratee, accumulator, thisArg)](#apidoc.element.lodash-node.object.transform)
- description and source-code
```javascript
function transform(object, iteratee, accumulator, thisArg) {
  var isArr = isArray(object) || isTypedArray(object);
  iteratee = baseCallback(iteratee, thisArg, 4);

  if (accumulator == null) {
    if (isArr || isObject(object)) {
      var Ctor = object.constructor;
      if (isArr) {
        accumulator = isArray(object) ? new Ctor : [];
      } else {
        accumulator = baseCreate(isFunction(Ctor) ? Ctor.prototype : undefined);
      }
    } else {
      accumulator = {};
    }
  }
  (isArr ? arrayEach : baseForOwn)(object, function(value, index, object) {
    return iteratee(accumulator, value, index, object);
  });
  return accumulator;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.values"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>values (object)](#apidoc.element.lodash-node.object.values)
- description and source-code
```javascript
function values(object) {
  return baseValues(object, keys(object));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.object.valuesIn"></a>[function <span class="apidocSignatureSpan">lodash-node.object.</span>valuesIn (object)](#apidoc.element.lodash-node.object.valuesIn)
- description and source-code
```javascript
function valuesIn(object) {
  return baseValues(object, keysIn(object));
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.partial"></a>[module lodash-node.partial](#apidoc.module.lodash-node.partial)

#### <a name="apidoc.element.lodash-node.partial.partial"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>partial ()](#apidoc.element.lodash-node.partial.partial)
- description and source-code
```javascript
partial = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.partial.placeholder"></a>[function <span class="apidocSignatureSpan">lodash-node.partial.</span>placeholder (value)](#apidoc.element.lodash-node.partial.placeholder)
- description and source-code
```javascript
function lodash(value) {
  if (isObjectLike(value) && !isArray(value) && !(value instanceof LazyWrapper)) {
    if (value instanceof LodashWrapper) {
      return value;
    }
    if (hasOwnProperty.call(value, '__chain__') && hasOwnProperty.call(value, '__wrapped__')) {
      return wrapperClone(value);
    }
  }
  return new LodashWrapper(value);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.partialRight"></a>[module lodash-node.partialRight](#apidoc.module.lodash-node.partialRight)

#### <a name="apidoc.element.lodash-node.partialRight.partialRight"></a>[function <span class="apidocSignatureSpan">lodash-node.</span>partialRight ()](#apidoc.element.lodash-node.partialRight.partialRight)
- description and source-code
```javascript
partialRight = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.partialRight.placeholder"></a>[function <span class="apidocSignatureSpan">lodash-node.partialRight.</span>placeholder (value)](#apidoc.element.lodash-node.partialRight.placeholder)
- description and source-code
```javascript
function lodash(value) {
  if (isObjectLike(value) && !isArray(value) && !(value instanceof LazyWrapper)) {
    if (value instanceof LodashWrapper) {
      return value;
    }
    if (hasOwnProperty.call(value, '__chain__') && hasOwnProperty.call(value, '__wrapped__')) {
      return wrapperClone(value);
    }
  }
  return new LodashWrapper(value);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.string"></a>[module lodash-node.string](#apidoc.module.lodash-node.string)

#### <a name="apidoc.element.lodash-node.string.camelCase"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>camelCase (string)](#apidoc.element.lodash-node.string.camelCase)
- description and source-code
```javascript
camelCase = function (string) {
  var index = -1,
      array = words(deburr(string)),
      length = array.length,
      result = '';

  while (++index < length) {
    result = callback(result, array[index], index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.capitalize"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>capitalize (string)](#apidoc.element.lodash-node.string.capitalize)
- description and source-code
```javascript
function capitalize(string) {
  string = baseToString(string);
  return string && (string.charAt(0).toUpperCase() + string.slice(1));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.deburr"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>deburr (string)](#apidoc.element.lodash-node.string.deburr)
- description and source-code
```javascript
function deburr(string) {
  string = baseToString(string);
  return string && string.replace(reLatin1, deburrLetter).replace(reComboMark, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.endsWith"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>endsWith (string, target, position)](#apidoc.element.lodash-node.string.endsWith)
- description and source-code
```javascript
function endsWith(string, target, position) {
  string = baseToString(string);
  target = (target + '');

  var length = string.length;
  position = position === undefined
    ? length
    : nativeMin(position < 0 ? 0 : (+position || 0), length);

  position -= target.length;
  return position >= 0 && string.indexOf(target, position) == position;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.escape"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>escape (string)](#apidoc.element.lodash-node.string.escape)
- description and source-code
```javascript
function escape(string) {
  // Reset 'lastIndex' because in IE < 9 'String#replace' does not.
  string = baseToString(string);
  return (string && reHasUnescapedHtml.test(string))
    ? string.replace(reUnescapedHtml, escapeHtmlChar)
    : string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.escapeRegExp"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>escapeRegExp (string)](#apidoc.element.lodash-node.string.escapeRegExp)
- description and source-code
```javascript
function escapeRegExp(string) {
  string = baseToString(string);
  return (string && reHasRegExpChars.test(string))
    ? string.replace(reRegExpChars, escapeRegExpChar)
    : (string || '(?:)');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.kebabCase"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>kebabCase (string)](#apidoc.element.lodash-node.string.kebabCase)
- description and source-code
```javascript
kebabCase = function (string) {
  var index = -1,
      array = words(deburr(string)),
      length = array.length,
      result = '';

  while (++index < length) {
    result = callback(result, array[index], index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.pad"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>pad (string, length, chars)](#apidoc.element.lodash-node.string.pad)
- description and source-code
```javascript
function pad(string, length, chars) {
  string = baseToString(string);
  length = +length;

  var strLength = string.length;
  if (strLength >= length || !nativeIsFinite(length)) {
    return string;
  }
  var mid = (length - strLength) / 2,
      leftLength = nativeFloor(mid),
      rightLength = nativeCeil(mid);

  chars = createPadding('', rightLength, chars);
  return chars.slice(0, leftLength) + string + chars;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.padLeft"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>padLeft (string, length, chars)](#apidoc.element.lodash-node.string.padLeft)
- description and source-code
```javascript
padLeft = function (string, length, chars) {
  string = baseToString(string);
  return (fromRight ? string : '') + createPadding(string, length, chars) + (fromRight ? '' : string);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.padRight"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>padRight (string, length, chars)](#apidoc.element.lodash-node.string.padRight)
- description and source-code
```javascript
padRight = function (string, length, chars) {
  string = baseToString(string);
  return (fromRight ? string : '') + createPadding(string, length, chars) + (fromRight ? '' : string);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.parseInt"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>parseInt (string, radix, guard)](#apidoc.element.lodash-node.string.parseInt)
- description and source-code
```javascript
function parseInt(string, radix, guard) {
  // Firefox < 21 and Opera < 15 follow ES3 for 'parseInt'.
  // Chrome fails to trim leading <BOM> whitespace characters.
  // See https://code.google.com/p/v8/issues/detail?id=3109 for more details.
  if (guard ? isIterateeCall(string, radix, guard) : radix == null) {
    radix = 0;
  } else if (radix) {
    radix = +radix;
  }
  string = trim(string);
  return nativeParseInt(string, radix || (reHasHexPrefix.test(string) ? 16 : 10));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.repeat"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>repeat (string, n)](#apidoc.element.lodash-node.string.repeat)
- description and source-code
```javascript
function repeat(string, n) {
  var result = '';
  string = baseToString(string);
  n = +n;
  if (n < 1 || !string || !nativeIsFinite(n)) {
    return result;
  }
  // Leverage the exponentiation by squaring algorithm for a faster repeat.
  // See https://en.wikipedia.org/wiki/Exponentiation_by_squaring for more details.
  do {
    if (n % 2) {
      result += string;
    }
    n = nativeFloor(n / 2);
    string += string;
  } while (n);

  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.snakeCase"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>snakeCase (string)](#apidoc.element.lodash-node.string.snakeCase)
- description and source-code
```javascript
snakeCase = function (string) {
  var index = -1,
      array = words(deburr(string)),
      length = array.length,
      result = '';

  while (++index < length) {
    result = callback(result, array[index], index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.startCase"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>startCase (string)](#apidoc.element.lodash-node.string.startCase)
- description and source-code
```javascript
startCase = function (string) {
  var index = -1,
      array = words(deburr(string)),
      length = array.length,
      result = '';

  while (++index < length) {
    result = callback(result, array[index], index);
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.startsWith"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>startsWith (string, target, position)](#apidoc.element.lodash-node.string.startsWith)
- description and source-code
```javascript
function startsWith(string, target, position) {
  string = baseToString(string);
  position = position == null
    ? 0
    : nativeMin(position < 0 ? 0 : (+position || 0), string.length);

  return string.lastIndexOf(target, position) == position;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.template"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>template (string, options, otherOptions)](#apidoc.element.lodash-node.string.template)
- description and source-code
```javascript
function template(string, options, otherOptions) {
  // Based on John Resig's 'tmpl' implementation (http://ejohn.org/blog/javascript-micro-templating/)
  // and Laura Doktorova's doT.js (https://github.com/olado/doT).
  var settings = templateSettings.imports._.templateSettings || templateSettings;

  if (otherOptions && isIterateeCall(string, options, otherOptions)) {
    options = otherOptions = undefined;
  }
  string = baseToString(string);
  options = assignWith(baseAssign({}, otherOptions || options), settings, assignOwnDefaults);

  var imports = assignWith(baseAssign({}, options.imports), settings.imports, assignOwnDefaults),
      importsKeys = keys(imports),
      importsValues = baseValues(imports, importsKeys);

  var isEscaping,
      isEvaluating,
      index = 0,
      interpolate = options.interpolate || reNoMatch,
      source = "__p += '";

  // Compile the regexp to match each delimiter.
  var reDelimiters = RegExp(
    (options.escape || reNoMatch).source + '|' +
    interpolate.source + '|' +
    (interpolate === reInterpolate ? reEsTemplate : reNoMatch).source + '|' +
    (options.evaluate || reNoMatch).source + '|$'
  , 'g');

  // Use a sourceURL for easier debugging.
  var sourceURL = 'sourceURL' in options ? '//# sourceURL=' + options.sourceURL + '\n' : '';

  string.replace(reDelimiters, function(match, escapeValue, interpolateValue, esTemplateValue, evaluateValue, offset) {
    interpolateValue || (interpolateValue = esTemplateValue);

    // Escape characters that can't be included in string literals.
    source += string.slice(index, offset).replace(reUnescapedString, escapeStringChar);

    // Replace delimiters with snippets.
    if (escapeValue) {
      isEscaping = true;
      source += "' +\n__e(" + escapeValue + ") +\n'";
    }
    if (evaluateValue) {
      isEvaluating = true;
      source += "';\n" + evaluateValue + ";\n__p += '";
    }
    if (interpolateValue) {
      source += "' +\n((__t = (" + interpolateValue + ")) == null ? '' : __t) +\n'";
    }
    index = offset + match.length;

    // The JS engine embedded in Adobe products requires returning the 'match'
    // string in order to produce the correct 'offset' value.
    return match;
  });

  source += "';\n";

  // If 'variable' is not specified wrap a with-statement around the generated
  // code to add the data object to the top of the scope chain.
  var variable = options.variable;
  if (!variable) {
    source = 'with (obj) {\n' + source + '\n}\n';
  }
  // Cleanup code by stripping empty strings.
  source = (isEvaluating ? source.replace(reEmptyStringLeading, '') : source)
    .replace(reEmptyStringMiddle, '$1')
    .replace(reEmptyStringTrailing, '$1;');

  // Frame code as the function body.
  source = 'function(' + (variable || 'obj') + ') {\n' +
    (variable
      ? ''
      : 'obj || (obj = {});\n'
    ) +
    "var __t, __p = ''" +
    (isEscaping
       ? ', __e = _.escape'
       : ''
    ) +
    (isEvaluating
      ? ', __j = Array.prototype.join;\n' +
        "function print() { __p += __j.call(arguments, '') }\n"
      : ';\n'
    ) +
    source +
    'return __p\n}';

  var result = attempt(function() {
    return Function(importsKeys, sourceURL + 'return ' + source).apply(undefined, importsValues);
  });

  // Provide the compiled function's source by its 'toString' method or
  // the 'source' property as a convenience for inlining compiled templates.
  result.source = source;
  if (isError(result)) {
    throw result;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.trim"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>trim (string, chars, guard)](#apidoc.element.lodash-node.string.trim)
- description and source-code
```javascript
function trim(string, chars, guard) {
  var value = string;
  string = baseToString(string);
  if (!string) {
    return string;
  }
  if (guard ? isIterateeCall(value, chars, guard) : chars == null) {
    return string.slice(trimmedLeftIndex(string), trimmedRightIndex(string) + 1);
  }
  chars = (chars + '');
  return string.slice(charsLeftIndex(string, chars), charsRightIndex(string, chars) + 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.trimLeft"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>trimLeft (string, chars, guard)](#apidoc.element.lodash-node.string.trimLeft)
- description and source-code
```javascript
function trimLeft(string, chars, guard) {
  var value = string;
  string = baseToString(string);
  if (!string) {
    return string;
  }
  if (guard ? isIterateeCall(value, chars, guard) : chars == null) {
    return string.slice(trimmedLeftIndex(string));
  }
  return string.slice(charsLeftIndex(string, (chars + '')));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.trimRight"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>trimRight (string, chars, guard)](#apidoc.element.lodash-node.string.trimRight)
- description and source-code
```javascript
function trimRight(string, chars, guard) {
  var value = string;
  string = baseToString(string);
  if (!string) {
    return string;
  }
  if (guard ? isIterateeCall(value, chars, guard) : chars == null) {
    return string.slice(0, trimmedRightIndex(string) + 1);
  }
  return string.slice(0, charsRightIndex(string, (chars + '')) + 1);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.trunc"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>trunc (string, options, guard)](#apidoc.element.lodash-node.string.trunc)
- description and source-code
```javascript
function trunc(string, options, guard) {
  if (guard && isIterateeCall(string, options, guard)) {
    options = undefined;
  }
  var length = DEFAULT_TRUNC_LENGTH,
      omission = DEFAULT_TRUNC_OMISSION;

  if (options != null) {
    if (isObject(options)) {
      var separator = 'separator' in options ? options.separator : separator;
      length = 'length' in options ? (+options.length || 0) : length;
      omission = 'omission' in options ? baseToString(options.omission) : omission;
    } else {
      length = +options || 0;
    }
  }
  string = baseToString(string);
  if (length >= string.length) {
    return string;
  }
  var end = length - omission.length;
  if (end < 1) {
    return omission;
  }
  var result = string.slice(0, end);
  if (separator == null) {
    return result + omission;
  }
  if (isRegExp(separator)) {
    if (string.slice(end).search(separator)) {
      var match,
          newEnd,
          substring = string.slice(0, end);

      if (!separator.global) {
        separator = RegExp(separator.source, (reFlags.exec(separator) || '') + 'g');
      }
      separator.lastIndex = 0;
      while ((match = separator.exec(substring))) {
        newEnd = match.index;
      }
      result = result.slice(0, newEnd == null ? end : newEnd);
    }
  } else if (string.indexOf(separator, end) != end) {
    var index = result.lastIndexOf(separator);
    if (index > -1) {
      result = result.slice(0, index);
    }
  }
  return result + omission;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.unescape"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>unescape (string)](#apidoc.element.lodash-node.string.unescape)
- description and source-code
```javascript
function unescape(string) {
  string = baseToString(string);
  return (string && reHasEscapedHtml.test(string))
    ? string.replace(reEscapedHtml, unescapeHtmlChar)
    : string;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.string.words"></a>[function <span class="apidocSignatureSpan">lodash-node.string.</span>words (string, pattern, guard)](#apidoc.element.lodash-node.string.words)
- description and source-code
```javascript
function words(string, pattern, guard) {
  if (guard && isIterateeCall(string, pattern, guard)) {
    pattern = undefined;
  }
  string = baseToString(string);
  return string.match(pattern || reWords) || [];
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.lodash-node.utility"></a>[module lodash-node.utility](#apidoc.module.lodash-node.utility)

#### <a name="apidoc.element.lodash-node.utility.attempt"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>attempt ()](#apidoc.element.lodash-node.utility.attempt)
- description and source-code
```javascript
attempt = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.callback"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>callback (func, thisArg, guard)](#apidoc.element.lodash-node.utility.callback)
- description and source-code
```javascript
function callback(func, thisArg, guard) {
  if (guard && isIterateeCall(func, thisArg, guard)) {
    thisArg = undefined;
  }
  return isObjectLike(func)
    ? matches(func)
    : baseCallback(func, thisArg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.constant"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>constant (value)](#apidoc.element.lodash-node.utility.constant)
- description and source-code
```javascript
function constant(value) {
  return function() {
    return value;
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.identity"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>identity (value)](#apidoc.element.lodash-node.utility.identity)
- description and source-code
```javascript
function identity(value) {
  return value;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.iteratee"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>iteratee (func, thisArg, guard)](#apidoc.element.lodash-node.utility.iteratee)
- description and source-code
```javascript
function callback(func, thisArg, guard) {
  if (guard && isIterateeCall(func, thisArg, guard)) {
    thisArg = undefined;
  }
  return isObjectLike(func)
    ? matches(func)
    : baseCallback(func, thisArg);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.matches"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>matches (source)](#apidoc.element.lodash-node.utility.matches)
- description and source-code
```javascript
function matches(source) {
  return baseMatches(baseClone(source, true));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.matchesProperty"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>matchesProperty (path, srcValue)](#apidoc.element.lodash-node.utility.matchesProperty)
- description and source-code
```javascript
function matchesProperty(path, srcValue) {
  return baseMatchesProperty(path, baseClone(srcValue, true));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.method"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>method ()](#apidoc.element.lodash-node.utility.method)
- description and source-code
```javascript
method = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.methodOf"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>methodOf ()](#apidoc.element.lodash-node.utility.methodOf)
- description and source-code
```javascript
methodOf = function () {
  var args = arguments,
      index = -1,
      length = nativeMax(args.length - start, 0),
      rest = Array(length);

  while (++index < length) {
    rest[index] = args[start + index];
  }
  switch (start) {
    case 0: return func.call(this, rest);
    case 1: return func.call(this, args[0], rest);
    case 2: return func.call(this, args[0], args[1], rest);
  }
  var otherArgs = Array(start + 1);
  index = -1;
  while (++index < start) {
    otherArgs[index] = args[index];
  }
  otherArgs[start] = rest;
  return func.apply(this, otherArgs);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.mixin"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>mixin (object, source, options)](#apidoc.element.lodash-node.utility.mixin)
- description and source-code
```javascript
function mixin(object, source, options) {
  var methodNames = baseFunctions(source, keys(source));

  var chain = true,
      index = -1,
      isFunc = isFunction(object),
      length = methodNames.length;

  if (options === false) {
    chain = false;
  } else if (isObject(options) && 'chain' in options) {
    chain = options.chain;
  }
  while (++index < length) {
    var methodName = methodNames[index],
        func = source[methodName];

    object[methodName] = func;
    if (isFunc) {
      object.prototype[methodName] = (function(func) {
        return function() {
          var chainAll = this.__chain__;
          if (chain || chainAll) {
            var result = object(this.__wrapped__),
                actions = result.__actions__ = arrayCopy(this.__actions__);

            actions.push({ 'func': func, 'args': arguments, 'thisArg': object });
            result.__chain__ = chainAll;
            return result;
          }
          return func.apply(object, arrayPush([this.value()], arguments));
        };
      }(func));
    }
  }
  return object;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.noop"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>noop ()](#apidoc.element.lodash-node.utility.noop)
- description and source-code
```javascript
function noop() {
  // No operation performed.
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.property"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>property (path)](#apidoc.element.lodash-node.utility.property)
- description and source-code
```javascript
function property(path) {
  return isKey(path) ? baseProperty(path) : basePropertyDeep(path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.propertyOf"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>propertyOf (object)](#apidoc.element.lodash-node.utility.propertyOf)
- description and source-code
```javascript
function propertyOf(object) {
  return function(path) {
    return baseGet(object, toPath(path), (path + ''));
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.range"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>range (start, end, step)](#apidoc.element.lodash-node.utility.range)
- description and source-code
```javascript
function range(start, end, step) {
  if (step && isIterateeCall(start, end, step)) {
    end = step = undefined;
  }
  start = +start || 0;
  step = step == null ? 1 : (+step || 0);

  if (end == null) {
    end = start;
    start = 0;
  } else {
    end = +end || 0;
  }
  // Use 'Array(length)' so engines like Chakra and V8 avoid slower modes.
  // See https://youtu.be/XAqIpGU8ZZk#t=17m25s for more details.
  var index = -1,
      length = nativeMax(nativeCeil((end - start) / (step || 1)), 0),
      result = Array(length);

  while (++index < length) {
    result[index] = start;
    start += step;
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.times"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>times (n, iteratee, thisArg)](#apidoc.element.lodash-node.utility.times)
- description and source-code
```javascript
function times(n, iteratee, thisArg) {
  n = nativeFloor(n);

  // Exit early to avoid a JSC JIT bug in Safari 8
  // where 'Array(0)' is treated as 'Array(1)'.
  if (n < 1 || !nativeIsFinite(n)) {
    return [];
  }
  var index = -1,
      result = Array(nativeMin(n, MAX_ARRAY_LENGTH));

  iteratee = bindCallback(iteratee, thisArg, 1);
  while (++index < n) {
    if (index < MAX_ARRAY_LENGTH) {
      result[index] = iteratee(index);
    } else {
      iteratee(index);
    }
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.lodash-node.utility.uniqueId"></a>[function <span class="apidocSignatureSpan">lodash-node.utility.</span>uniqueId (prefix)](#apidoc.element.lodash-node.utility.uniqueId)
- description and source-code
```javascript
function uniqueId(prefix) {
  var id = ++idCounter;
  return baseToString(prefix) + id;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
