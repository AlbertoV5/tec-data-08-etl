- [Extract, Transform, Load](#orgf23040c)



<a id="orgf23040c"></a>

# Extract, Transform, Load

![img](./movies_query.png)

```sql
SELECT COUNT(*) FROM movies;
```

<table><tr><th>count</th></tr><tr><td>6051</td></tr></table>

```sql
SELECT index, imdb_id FROM movies ORDER BY index DESC LIMIT 10;
```

<table><tr><th>index</th><th>imdb_id</th></tr><tr><td>6051</td><td>tt3859310</td></tr><tr><td>6050</td><td>tt5795086</td></tr><tr><td>6049</td><td>tt6304162</td></tr><tr><td>6048</td><td>tt5390066</td></tr><tr><td>6047</td><td>tt5639354</td></tr><tr><td>6046</td><td>tt3567666</td></tr><tr><td>6045</td><td>tt4765284</td></tr><tr><td>6044</td><td>tt1724970</td></tr><tr><td>6043</td><td>tt5726616</td></tr><tr><td>6042</td><td>tt0974015</td></tr></table>
